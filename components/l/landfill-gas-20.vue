<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrmndgb7b.css';
import '../../css/i/i1s8vsfit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vrmndgb7b"/><path class="i1s8vsfit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:landfill-gas-20" /></template>
