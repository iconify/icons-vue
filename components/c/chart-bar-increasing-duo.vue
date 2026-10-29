<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qgwbb0buk.css';
import '../../css/s/skn8acc-z.css';
import '../../css/r/ralcq11vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="qgwbb0buk"/><path class="skn8acc-z wm-a"/><path class="ralcq11vz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-bar-increasing-duo" /></template>
