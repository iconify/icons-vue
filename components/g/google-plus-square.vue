<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1w7dacyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="r1w7dacyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:google-plus-square" /></template>
