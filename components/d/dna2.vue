<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixi6hl2_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ixi6hl2_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dna2" /></template>
