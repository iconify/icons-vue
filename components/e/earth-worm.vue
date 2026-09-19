<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oodhp_big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oodhp_big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:earth-worm" /></template>
