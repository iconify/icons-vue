<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdp5l0b5n.css';
import '../../css/z/zyix_fbli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qdp5l0b5n"/><path class="zyix_fbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chart-scatter-48" /></template>
