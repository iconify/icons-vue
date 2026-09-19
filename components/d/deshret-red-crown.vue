<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rj1h_n8dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rj1h_n8dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:deshret-red-crown" /></template>
