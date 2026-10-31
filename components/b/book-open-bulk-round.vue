<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h76dexwai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h76dexwai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open-bulk-round" /></template>
