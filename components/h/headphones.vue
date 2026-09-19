<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0gr9_xdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j0gr9_xdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:headphones" /></template>
