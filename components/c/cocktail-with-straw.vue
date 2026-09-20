<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5-e9pb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="j5-e9pb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cocktail-with-straw" /></template>
