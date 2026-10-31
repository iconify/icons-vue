<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/o/og399p1rd.css';
import '../../css/u/uuaa4bcqw.css';
import '../../css/g/giwb81ztw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="og399p1rd wm-shadow"/><path class="uuaa4bcqw wm-shadow"/><path class="giwb81ztw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:chart-scatter" /></template>
