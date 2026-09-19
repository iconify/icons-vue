<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx-1ftb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jx-1ftb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:freedom-dove" /></template>
