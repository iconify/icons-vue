<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg-0zhwkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hg-0zhwkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:female" /></template>
