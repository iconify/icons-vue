<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk90b0i-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mk90b0i-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:fire-spell-cast" /></template>
