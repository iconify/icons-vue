<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/b/bov66nrpl.css';
import '../../css/h/hfi5e-rtf.css';
import '../../css/u/um2mdjbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="bov66nrpl wm-k"/><path class="hfi5e-rtf wm-a"/><path class="um2mdjbzw wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:list" /></template>
