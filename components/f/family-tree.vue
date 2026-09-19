<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rnu_wrw5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rnu_wrw5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:family-tree" /></template>
