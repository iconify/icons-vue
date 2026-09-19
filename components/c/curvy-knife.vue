<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbe650b-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nbe650b-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:curvy-knife" /></template>
