<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf5rwx65l.css';
import '../../css/d/d0d0ko1nq.css';
import '../../css/n/nnc9b285l.css';
import '../../css/m/mziiijuxo.css';
import '../../css/j/j4a5z979b.css';
import '../../css/n/nksthvbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":180,"height":180};
const content = `<g class="yf5rwx65l"><path class="d0d0ko1nq"/><path clip-rule="evenodd" class="nnc9b285l"/><path clip-rule="evenodd" class="mziiijuxo"/><path clip-rule="evenodd" class="j4a5z979b"/><path clip-rule="evenodd" class="nksthvbor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lego" /></template>
