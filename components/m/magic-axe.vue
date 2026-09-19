<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dk4oliu5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dk4oliu5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magic-axe" /></template>
