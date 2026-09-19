<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fo_akvmhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fo_akvmhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:film-spool" /></template>
