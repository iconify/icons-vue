<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/d/d0wnsrbyc.css';
import '../../css/c/cw36_6mco.css';
import '../../css/a/ampev-b2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="d0wnsrbyc wm-k"/><path class="cw36_6mco wm-a"/><path class="ampev-b2a wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:chart-line" /></template>
