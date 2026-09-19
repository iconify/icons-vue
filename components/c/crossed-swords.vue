<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bp072-bjg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bp072-bjg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:crossed-swords" /></template>
