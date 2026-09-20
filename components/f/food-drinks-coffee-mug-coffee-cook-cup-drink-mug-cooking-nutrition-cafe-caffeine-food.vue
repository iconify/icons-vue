<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbsp_yblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="kbsp_yblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:food-drinks-coffee-mug-coffee-cook-cup-drink-mug-cooking-nutrition-cafe-caffeine-food" /></template>
