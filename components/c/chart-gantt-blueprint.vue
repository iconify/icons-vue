<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/t/t57gzpbxz.css';
import '../../css/l/ls35do6ly.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/g/gj-26l82r.css';
import '../../css/k/k2jm9_qyv.css';
import '../../css/q/qo8ilkn6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="t57gzpbxz wm-deco"/><path class="ls35do6ly wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="gj-26l82r wm-k"/><path class="k2jm9_qyv wm-a"/><path class="qo8ilkn6e wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chart-gantt-blueprint" /></template>
