<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-d_g7knk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-d_g7knk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:hobbit-door" /></template>
