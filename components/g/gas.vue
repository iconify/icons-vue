<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqrgs8bmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gqrgs8bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:gas" /></template>
