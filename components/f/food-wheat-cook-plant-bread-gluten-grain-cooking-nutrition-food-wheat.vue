<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j61_c6bws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="j61_c6bws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:food-wheat-cook-plant-bread-gluten-grain-cooking-nutrition-food-wheat" /></template>
