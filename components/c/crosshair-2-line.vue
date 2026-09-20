<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rln_3myxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rln_3myxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:crosshair-2-line" /></template>
