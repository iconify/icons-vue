<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia51n3hgg.css';
import '../../css/t/tv9ekks-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ia51n3hgg"/><path class="tv9ekks-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:laundry-basket-20-bold" /></template>
