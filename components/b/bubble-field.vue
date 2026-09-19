<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf62d2b6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uf62d2b6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bubble-field" /></template>
