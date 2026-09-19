<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w0ymd3_9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w0ymd3_9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:giant-squid" /></template>
