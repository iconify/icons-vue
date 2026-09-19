<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c210-8tfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c210-8tfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-food-menu" /></template>
