<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scyd3qb2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scyd3qb2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:gallery-thumbnails-sharp" /></template>
