<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5q0sh-om.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p5q0sh-om"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fishing-boat" /></template>
