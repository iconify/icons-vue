<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8maq5b0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u8maq5b0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-wind-20" /></template>
