<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/q/qotkwl1bf.css';
import '../../css/o/omjh3bb_f.css';
import '../../css/c/cnw7n79ym.css';
import '../../css/x/x_8sqqbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="qotkwl1bf"/><path class="omjh3bb_f"/><path class="cnw7n79ym"/><path class="x_8sqqbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:drink" /></template>
