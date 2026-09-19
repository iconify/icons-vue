<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dmbvezfkt.css';
import '../../css/m/m8842cbyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="dmbvezfkt"/><path class="m8842cbyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:apple" /></template>
