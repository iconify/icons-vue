<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nj3s65blm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nj3s65blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:circle-sparks" /></template>
