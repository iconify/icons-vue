<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf1zivb8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uf1zivb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fox-head" /></template>
