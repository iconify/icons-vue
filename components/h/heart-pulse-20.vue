<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2zh3obzl.css';
import '../../css/u/upem778kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e2zh3obzl"/><path class="upem778kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heart-pulse-20" /></template>
