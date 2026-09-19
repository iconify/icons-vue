<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nla3em28f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nla3em28f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ibis" /></template>
