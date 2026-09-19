<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tb64df4eu.css';
import '../../css/a/alt68kdnd.css';
import '../../css/c/cj00blbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><rect transform="rotate(45 35.193 5.322)" class="tb64df4eu"/><path class="alt68kdnd"/><rect transform="rotate(30 33.268 12.34)" class="cj00blbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:electronic-pen" /></template>
