<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1si40b_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n1si40b_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-sun-rain-48" /></template>
