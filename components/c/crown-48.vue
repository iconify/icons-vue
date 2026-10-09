<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw607l8ol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cw607l8ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crown-48" /></template>
