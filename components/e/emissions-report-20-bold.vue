<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny-w6qbwa.css';
import '../../css/p/pv7m710be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ny-w6qbwa"/><path class="pv7m710be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:emissions-report-20-bold" /></template>
