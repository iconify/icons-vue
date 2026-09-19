<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sec0djbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sec0djbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-king-clubs" /></template>
