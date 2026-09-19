<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xmjju991p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xmjju991p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crowned-skull" /></template>
