<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/s/sjv9wy0ft.css';
import '../../css/h/hjd5wlsvp.css';
import '../../css/c/cy-437bpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="sjv9wy0ft wm-shadow"/><path class="hjd5wlsvp wm-shadow"/><path class="cy-437bpc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:chart-bar-horizontal" /></template>
