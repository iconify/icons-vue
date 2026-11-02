<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zehq18b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zehq18b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-big-down-dash-fill" /></template>
