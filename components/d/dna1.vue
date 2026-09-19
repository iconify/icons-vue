<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m46one6gc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m46one6gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dna1" /></template>
