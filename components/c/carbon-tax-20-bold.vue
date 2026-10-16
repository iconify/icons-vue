<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iua8clh6p.css';
import '../../css/d/d8lollj3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iua8clh6p"/><path class="d8lollj3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-tax-20-bold" /></template>
