<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx1d-z-yo.css';
import '../../css/g/gvnofzq5q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rx1d-z-yo"/><path class="gvnofzq5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:arrows-vertical-48" /></template>
