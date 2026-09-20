<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ttu_k9btm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="ttu_k9btm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:hypothesis-square" /></template>
