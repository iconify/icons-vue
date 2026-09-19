<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2bra0b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h2bra0b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cracked-ball-dunk" /></template>
