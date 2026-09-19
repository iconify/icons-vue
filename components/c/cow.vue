<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dj-8enh6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dj-8enh6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cow" /></template>
