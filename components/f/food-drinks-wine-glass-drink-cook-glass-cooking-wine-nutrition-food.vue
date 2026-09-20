<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu06apb_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="xu06apb_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:food-drinks-wine-glass-drink-cook-glass-cooking-wine-nutrition-food" /></template>
