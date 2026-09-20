<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvuscacwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="fvuscacwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:jai-alai-cesta-and-ball" /></template>
