<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi5qd8jiy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xi5qd8jiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:magnifying-glass" /></template>
