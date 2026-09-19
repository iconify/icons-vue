<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af0yy_bnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="af0yy_bnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-ray" /></template>
