<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znca9pbnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="znca9pbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:electrical-crescent" /></template>
