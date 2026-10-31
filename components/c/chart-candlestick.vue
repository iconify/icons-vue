<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/d/d2kju4cpp.css';
import '../../css/t/thamkpbss.css';
import '../../css/k/klofeg8-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="d2kju4cpp wm-shadow"/><path class="thamkpbss wm-shadow"/><path class="klofeg8-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:chart-candlestick" /></template>
