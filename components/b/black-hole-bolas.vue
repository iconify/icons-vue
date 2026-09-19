<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_jnz1lnv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h_jnz1lnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:black-hole-bolas" /></template>
