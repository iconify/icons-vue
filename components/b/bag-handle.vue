<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg6kdcc7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dg6kdcc7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:bag-handle" /></template>
