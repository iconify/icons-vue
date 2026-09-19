<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4u_gzbvh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k4u_gzbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:doorway" /></template>
