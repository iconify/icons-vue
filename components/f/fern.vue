<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0m2jmbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h0m2jmbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fern" /></template>
