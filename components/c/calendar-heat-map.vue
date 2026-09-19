<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpyx0diih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cpyx0diih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calendar-heat-map" /></template>
