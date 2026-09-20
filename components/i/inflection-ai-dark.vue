<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6xx_uqow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a6xx_uqow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:inflection-ai-dark" /></template>
