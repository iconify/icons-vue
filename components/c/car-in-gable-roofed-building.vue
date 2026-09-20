<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mabj5bb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="mabj5bb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-in-gable-roofed-building" /></template>
