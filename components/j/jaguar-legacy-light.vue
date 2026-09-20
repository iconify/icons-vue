<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmbmkcbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1045.7,"height":85};
const content = `<path class="rmbmkcbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jaguar-legacy-light" /></template>
