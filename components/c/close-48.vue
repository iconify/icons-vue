<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpcpxlb-i.css';
import '../../css/u/uspm4fblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gpcpxlb-i"/><path class="uspm4fblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:close-48" /></template>
