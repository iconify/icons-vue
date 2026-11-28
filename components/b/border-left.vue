<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/du-n6bmny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="du-n6bmny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:border-left" /></template>
