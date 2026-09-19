<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyu36cbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fyu36cbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:greek-sphinx" /></template>
