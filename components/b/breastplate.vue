<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8e_b-bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f8e_b-bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:breastplate" /></template>
