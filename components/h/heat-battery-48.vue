<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pntg1acwg.css';
import '../../css/p/pu7nh0bwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pntg1acwg"/><path class="pu7nh0bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-battery-48" /></template>
