<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eooamkbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eooamkbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cart-plus" /></template>
