<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/za087rbox.css';
import '../../css/q/qeugsjbsl.css';
import '../../css/y/y1g8qib3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="za087rbox"/><path clip-rule="evenodd" class="qeugsjbsl"/><path class="y1g8qib3o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:concept-sharing" /></template>
