<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7wmwym2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="m7wmwym2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-down-2" /></template>
