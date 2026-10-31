<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/mun-f5k6r.css';
import '../../css/f/f6bq3-oon.css';
import '../../css/y/yb2eb2rfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="mun-f5k6r wm-shadow"/><path class="f6bq3-oon wm-shadow"/><path class="yb2eb2rfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:list-checks" /></template>
