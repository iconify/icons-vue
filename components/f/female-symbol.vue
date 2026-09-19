<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4uzobcex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="w4uzobcex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:female-symbol" /></template>
