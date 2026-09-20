<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi7cakbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="fi7cakbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:bath" /></template>
