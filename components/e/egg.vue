<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/u80ovujow.css';
import '../../css/w/w0ggckbeu.css';
import '../../css/p/p7b_6qbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="u80ovujow"/><path class="w0ggckbeu"/><path class="p7b_6qbai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:egg" /></template>
