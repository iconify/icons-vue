<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_vs-hd3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_vs-hd3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:black-bar" /></template>
