<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxbg4sb7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mxbg4sb7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cosmic-egg" /></template>
