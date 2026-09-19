<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/t/t4lfr94ic.css';
import '../../css/e/es2y4_69g.css';
import '../../css/l/l3a42pa9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="t4lfr94ic"/><path class="es2y4_69g"/><path class="l3a42pa9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:cake-two" /></template>
