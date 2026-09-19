<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9lw1xbzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e9lw1xbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:cauldron" /></template>
