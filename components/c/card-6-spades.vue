<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tif1ywbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tif1ywbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-6-spades" /></template>
