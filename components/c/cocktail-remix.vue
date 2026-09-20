<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7zb98bfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c7zb98bfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:cocktail-remix" /></template>
