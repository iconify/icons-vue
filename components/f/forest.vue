<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4l03cc6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k4l03cc6f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:forest" /></template>
