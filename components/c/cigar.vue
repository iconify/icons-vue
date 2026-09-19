<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z47rp0b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z47rp0b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cigar" /></template>
