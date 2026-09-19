<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f83lo_bbe.css';
import '../../css/n/nnd46w4ky.css';
import '../../css/h/hd4_l7bgy.css';
import '../../css/e/e04d3abid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="f83lo_bbe"/><g class="nnd46w4ky"><path class="hd4_l7bgy"/><path class="e04d3abid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:internal" /></template>
