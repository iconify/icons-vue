<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2gcbl84d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h2gcbl84d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:chess-king" /></template>
