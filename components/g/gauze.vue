<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/uyseoq3ur.css';
import '../../css/x/x6mnf95_s.css';
import '../../css/q/qw1suyb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><circle class="uyseoq3ur"/><circle class="x6mnf95_s"/><path class="qw1suyb4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:gauze" /></template>
