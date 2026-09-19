<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/m/mhrr42g8a.css';
import '../../css/u/u365hhbxy.css';
import '../../css/l/l7sdvlbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="mhrr42g8a"/><circle class="u365hhbxy"/><path class="l7sdvlbrp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:history-query" /></template>
