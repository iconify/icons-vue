<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fp3y8bb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fp3y8bb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:magic-gate" /></template>
