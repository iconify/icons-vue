<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/l/l7l825xyg.css';
import '../../css/r/ra2aarbtt.css';
import '../../css/l/l-dl82p6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="l7l825xyg wm-k"/><path class="ra2aarbtt wm-a"/><path class="l-dl82p6a wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:copy-check" /></template>
