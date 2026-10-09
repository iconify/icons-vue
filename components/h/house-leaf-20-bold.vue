<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/coivkzecr.css';
import '../../css/r/rjaab2bfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="coivkzecr"/><path class="rjaab2bfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-leaf-20-bold" /></template>
