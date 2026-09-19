<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fv8gbu0fn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fv8gbu0fn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:google-wordmark" /></template>
