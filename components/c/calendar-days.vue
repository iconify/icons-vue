<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/c/cf7nx1v6t.css';
import '../../css/m/m6joo21nb.css';
import '../../css/o/ovocp5a6o.css';
import '../../css/l/liegl_bla.css';
import '../../css/y/y5aloinyc.css';
import '../../css/q/qg1g-jbjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="cf7nx1v6t wm-shadow"/><path class="m6joo21nb"/><path class="ovocp5a6o"/><path class="liegl_bla"/><path class="y5aloinyc"/><path class="qg1g-jbjs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-retro:calendar-days" /></template>
