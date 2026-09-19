<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjqkqmbdp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="hjqkqmbdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:angle-double-right" /></template>
