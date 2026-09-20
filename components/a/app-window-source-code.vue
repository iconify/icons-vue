<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ib32nnbtb.css';
import '../../css/f/fp01zm4es.css';
import '../../css/c/ch1feccze.css';
import '../../css/l/l0hmyvbtb.css';
import '../../css/v/vpvffyb2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ib32nnbtb"/><path clip-rule="evenodd" class="fp01zm4es"/><path clip-rule="evenodd" class="ch1feccze"/><path clip-rule="evenodd" class="l0hmyvbtb"/><path class="vpvffyb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:app-window-source-code" /></template>
