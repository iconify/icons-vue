<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xck5rbc3z.css';
import '../../css/c/co11bsb3j.css';
import '../../css/q/qj5tj5n2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="xck5rbc3z"><path class="co11bsb3j"/><path class="qj5tj5n2x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:graph-bar-increase" /></template>
