<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpd1w5bao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rpd1w5bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crystal-bars" /></template>
