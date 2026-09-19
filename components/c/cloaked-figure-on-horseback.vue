<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s73pzob8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s73pzob8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cloaked-figure-on-horseback" /></template>
