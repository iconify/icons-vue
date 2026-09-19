<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhvq4ybnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mhvq4ybnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:category-fill" /></template>
