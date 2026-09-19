<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcos6abkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fcos6abkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-4-spades" /></template>
