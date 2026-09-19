<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn3x2lbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cn3x2lbne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:car-key" /></template>
