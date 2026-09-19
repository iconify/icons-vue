<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly-908bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ly-908bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:executioner-hood" /></template>
