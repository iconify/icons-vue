<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/waqu08mrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="waqu08mrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:card-exchange" /></template>
