<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlynum9nh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlynum9nh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chart-bar-stacked" /></template>
