<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1co_sb-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r1co_sb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:condylura-skull" /></template>
