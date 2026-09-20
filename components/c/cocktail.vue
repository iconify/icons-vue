<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1ni-gb-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1ni-gb-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:cocktail" /></template>
