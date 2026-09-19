<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgv36mbha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zgv36mbha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:interlocking-rings-stroke-16" /></template>
