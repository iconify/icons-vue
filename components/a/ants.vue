<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vha8znr2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vha8znr2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ants" /></template>
