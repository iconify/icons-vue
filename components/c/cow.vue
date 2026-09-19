<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dycx40bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2176,"height":1664};
const content = `<path class="dycx40bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vs:cow" /></template>
