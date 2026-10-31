<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/i/i309x2b5e.css';
import '../../css/g/gc9ew1bqh.css';
import '../../css/l/l2fpngjgy.css';
import '../../css/w/wqt3r3b9i.css';
import '../../css/w/wnveq1bjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="i309x2b5e"/><path class="gc9ew1bqh wm-shine"/><path class="l2fpngjgy wm-k"/><path class="wm-a wqt3r3b9i"/><path class="wm-deco wnveq1bjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:folder-plus" /></template>
