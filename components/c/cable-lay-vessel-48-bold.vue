<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty8a93bmr.css';
import '../../css/r/rzu6pacwb.css';
import '../../css/p/pvt3vvkbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ty8a93bmr"/><path class="rzu6pacwb"/><path class="pvt3vvkbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cable-lay-vessel-48-bold" /></template>
