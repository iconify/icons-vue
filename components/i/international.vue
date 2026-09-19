<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o93lq-byo.css';
import '../../css/m/mfaj5_b9w.css';
import '../../css/d/dmx9fugvp.css';
import '../../css/h/hi6vwvbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="o93lq-byo"><path class="mfaj5_b9w"/><path class="dmx9fugvp"/><path class="hi6vwvbkm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:international" /></template>
