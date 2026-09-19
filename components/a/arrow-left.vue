<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th6h8b04z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="th6h8b04z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:arrow-left" /></template>
