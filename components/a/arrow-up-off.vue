<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qrodqjb4o.css';
import '../../css/y/y_d3_dbln.css';
import '../../css/t/ttseslbft.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="qrodqjb4o"/><path clip-rule="evenodd" class="y_d3_dbln"/><path clip-rule="evenodd" class="ttseslbft"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:arrow-up-off" /></template>
