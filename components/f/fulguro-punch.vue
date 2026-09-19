<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrax578cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nrax578cf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fulguro-punch" /></template>
