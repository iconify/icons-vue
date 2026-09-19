<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpiskl3ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cpiskl3ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:extension-puzzle-outline" /></template>
