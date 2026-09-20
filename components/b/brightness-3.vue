<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cv-z9s63g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cv-z9s63g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:brightness-3" /></template>
