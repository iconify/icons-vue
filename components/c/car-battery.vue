<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxoeecc-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fxoeecc-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:car-battery" /></template>
