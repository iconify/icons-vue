<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jd9tt7pmf.css';
import '../../css/u/uv305zbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jd9tt7pmf"/><path class="uv305zbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:data-pipeline-48-bold" /></template>
