<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt0m3bcxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rt0m3bcxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:highlighter" /></template>
