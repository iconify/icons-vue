<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hltu5yboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hltu5yboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:laptop3-filled" /></template>
