<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtu6otbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vtu6otbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:annoyed" /></template>
