<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ampd2yblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ampd2yblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:equal-box" /></template>
