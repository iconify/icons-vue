<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e7bi54bti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e7bi54bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:calculator" /></template>
