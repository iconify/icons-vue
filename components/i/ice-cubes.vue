<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dri8jfb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dri8jfb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ice-cubes" /></template>
