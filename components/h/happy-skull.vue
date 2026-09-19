<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy-u7bcsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uy-u7bcsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:happy-skull" /></template>
