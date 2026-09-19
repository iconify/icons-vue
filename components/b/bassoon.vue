<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfqnmcj5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tfqnmcj5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bassoon" /></template>
