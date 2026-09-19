<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj2w_j80p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kj2w_j80p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:disc" /></template>
