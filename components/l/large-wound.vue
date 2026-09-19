<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gl3-q-bps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gl3-q-bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:large-wound" /></template>
