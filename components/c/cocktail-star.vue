<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxknf4tak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxknf4tak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cocktail-star" /></template>
