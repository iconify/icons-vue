<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ka83c5b9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka83c5b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:ampersand" /></template>
