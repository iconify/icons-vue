<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy0sv1baw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jy0sv1baw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:celebration-fire" /></template>
