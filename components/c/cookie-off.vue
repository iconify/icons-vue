<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc3-dh2aj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc3-dh2aj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cookie-off" /></template>
