<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dacf7bcvi.css';
import '../../css/p/poyb6lb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dacf7bcvi"/><path class="poyb6lb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:clamp-meter-48-bold" /></template>
