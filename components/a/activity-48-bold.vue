<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9_on4g5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c9_on4g5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:activity-48-bold" /></template>
