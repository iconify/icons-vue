<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmt269wze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rmt269wze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:broom" /></template>
