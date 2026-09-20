<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/awfw_5bbu.css';
import '../../css/q/q4z7accis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<g class="h01tyzbfu"><path class="awfw_5bbu"/><path class="q4z7accis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:heart-circle-outline" /></template>
