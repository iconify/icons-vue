<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi434z6ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi434z6ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bullseye-arrow" /></template>
