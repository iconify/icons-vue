<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x07oq7k1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x07oq7k1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:bookmark-20-bold" /></template>
