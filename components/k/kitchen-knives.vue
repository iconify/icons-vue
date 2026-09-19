<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lhe5w9bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lhe5w9bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:kitchen-knives" /></template>
