<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_d4iy4kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a_d4iy4kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:euro" /></template>
