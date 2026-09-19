<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu0i6sb0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tu0i6sb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:drop-earrings" /></template>
