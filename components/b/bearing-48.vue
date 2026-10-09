<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2g9qy8wl.css';
import '../../css/x/x89mfs52m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2g9qy8wl"/><path class="x89mfs52m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bearing-48" /></template>
