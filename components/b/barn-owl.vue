<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohivtub_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ohivtub_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:barn-owl" /></template>
