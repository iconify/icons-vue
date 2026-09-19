<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu02b2pci.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mu02b2pci"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:caravel" /></template>
