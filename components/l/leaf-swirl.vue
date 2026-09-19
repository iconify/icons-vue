<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w30-vrati.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w30-vrati"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:leaf-swirl" /></template>
