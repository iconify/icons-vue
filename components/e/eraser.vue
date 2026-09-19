<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e25xsfz0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="e25xsfz0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:eraser" /></template>
