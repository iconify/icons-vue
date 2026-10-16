<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5e3kibxu.css';
import '../../css/d/d2h5byb5d.css';
import '../../css/p/pqlptybrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s5e3kibxu"/><path class="d2h5byb5d"/><path class="pqlptybrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flow-meter-48" /></template>
