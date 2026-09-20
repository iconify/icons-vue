<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynvcx2b1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1549,"height":1881};
const content = `<path class="ynvcx2b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:avanza" /></template>
