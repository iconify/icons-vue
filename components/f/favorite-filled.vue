<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zum3w4bjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zum3w4bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:favorite-filled" /></template>
