<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7wlu5qtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="o7wlu5qtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gable-roofed-building" /></template>
