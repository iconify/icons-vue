<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4yrw2bbq.css';
import '../../css/e/e6lx946pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c4yrw2bbq"/><path class="e6lx946pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-cylinder-48" /></template>
