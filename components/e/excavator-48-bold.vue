<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dswf7-2aj.css';
import '../../css/m/mzptizb4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dswf7-2aj"/><path class="mzptizb4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:excavator-48-bold" /></template>
