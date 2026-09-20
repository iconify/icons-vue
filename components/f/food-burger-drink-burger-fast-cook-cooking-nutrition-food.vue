<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gyaawlnzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gyaawlnzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:food-burger-drink-burger-fast-cook-cooking-nutrition-food" /></template>
