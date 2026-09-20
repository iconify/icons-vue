<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0u3abb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0u3abb0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:letter-b" /></template>
