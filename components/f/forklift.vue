<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8m4j_b_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z8m4j_b_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:forklift" /></template>
