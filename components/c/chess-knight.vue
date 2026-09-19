<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sdy47f24p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sdy47f24p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chess-knight" /></template>
