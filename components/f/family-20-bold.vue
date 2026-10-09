<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-_unibko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u-_unibko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:family-20-bold" /></template>
