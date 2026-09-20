<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pszw-h5hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pszw-h5hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-j" /></template>
