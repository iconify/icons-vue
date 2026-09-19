<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8v-62bax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u8v-62bax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dolmen" /></template>
