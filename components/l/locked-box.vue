<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlik1cyno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rlik1cyno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:locked-box" /></template>
