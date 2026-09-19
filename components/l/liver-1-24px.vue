<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwnx4pakb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwnx4pakb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:liver-1-24px" /></template>
