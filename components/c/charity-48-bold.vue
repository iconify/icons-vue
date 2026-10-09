<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlmlrhbpp.css';
import '../../css/c/cyronpb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zlmlrhbpp"/><path class="cyronpb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:charity-48-bold" /></template>
