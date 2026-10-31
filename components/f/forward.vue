<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/b/bykj-8ldy.css';
import '../../css/e/e7970wbtu.css';
import '../../css/e/e78k15v9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="bykj-8ldy wm-k"/><path class="e7970wbtu wm-a"/><path class="e78k15v9f wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:forward" /></template>
