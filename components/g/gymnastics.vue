<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti4q6eknm.css';
import '../../css/i/iiv6nwbrq.css';
import '../../css/n/nzovm6bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="iiv6nwbrq"/><path class="nzovm6bgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:gymnastics" /></template>
