<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d62yhwbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d62yhwbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chisel" /></template>
