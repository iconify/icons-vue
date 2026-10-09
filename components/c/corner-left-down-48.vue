<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5xf0acau.css';
import '../../css/k/kf6co47ks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y5xf0acau"/><path class="kf6co47ks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-left-down-48" /></template>
