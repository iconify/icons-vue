<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_w8mhbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i_w8mhbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:headphones-20-bold" /></template>
