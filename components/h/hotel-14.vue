<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lafomvmft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="lafomvmft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:hotel-14" /></template>
