<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/f/f667w6b2q.css';
import '../../css/c/czwr0-f-r.css';
import '../../css/j/jmvv3kbnk.css';
import '../../css/y/yvr-duh2e.css';
import '../../css/i/i1g1qkwrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="f667w6b2q"/><path class="czwr0-f-r wm-shine"/><path class="jmvv3kbnk wm-k"/><path class="wm-a yvr-duh2e"/><path class="i1g1qkwrt wm-deco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:calendar-days" /></template>
