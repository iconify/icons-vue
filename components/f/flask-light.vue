<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0r1s99fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u0r1s99fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:flask-light" /></template>
