<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt8f-3eoh.css';
import '../../css/u/u8g1crnse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dt8f-3eoh"/><path class="u8g1crnse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-star-20-bold" /></template>
