<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d-5ihx0_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d-5ihx0_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:expense" /></template>
