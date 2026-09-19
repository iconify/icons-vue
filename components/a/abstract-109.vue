<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3d09_w4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z3d09_w4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-109" /></template>
