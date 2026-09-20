<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_m8x9bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="x_m8x9bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:impactstory-square" /></template>
