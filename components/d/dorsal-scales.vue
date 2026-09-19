<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyilz1b9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vyilz1b9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dorsal-scales" /></template>
