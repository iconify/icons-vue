<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikuw9ybyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ikuw9ybyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:clay-brick" /></template>
