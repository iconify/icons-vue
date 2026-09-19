<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjdk5_b1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mjdk5_b1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ceiling-barnacle" /></template>
