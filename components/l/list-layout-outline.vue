<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upz5ji1nn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="upz5ji1nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:list-layout-outline" /></template>
