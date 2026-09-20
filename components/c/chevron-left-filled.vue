<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo9ts0bej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo9ts0bej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chevron-left-filled" /></template>
