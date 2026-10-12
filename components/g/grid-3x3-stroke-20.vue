<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clczj4b0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="clczj4b0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:grid-3x3-stroke-20" /></template>
