<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4mjjratt.css';
import '../../css/d/d45xejkbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d4mjjratt"/><path class="d45xejkbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:align-bottom-20-bold" /></template>
