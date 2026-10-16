<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvyr40bsv.css';
import '../../css/g/gm9nibcja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dvyr40bsv"/><path class="gm9nibcja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:connector-mcs-48" /></template>
