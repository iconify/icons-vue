<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jeuq6bc2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jeuq6bc2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:box-cutter" /></template>
