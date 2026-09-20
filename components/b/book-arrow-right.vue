<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tym262xzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tym262xzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:book-arrow-right" /></template>
