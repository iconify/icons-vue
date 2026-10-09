<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0649ib9x.css';
import '../../css/e/e6u7bf88s.css';
import '../../css/n/nyx-ipbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l0649ib9x"/><path class="e6u7bf88s"/><path class="nyx-ipbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hydraulic-press-20" /></template>
