<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ms6ew-l8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ms6ew-l8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrow-big-up-48" /></template>
