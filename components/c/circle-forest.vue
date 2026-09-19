<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av7iwkbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="av7iwkbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:circle-forest" /></template>
