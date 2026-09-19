<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d771kzbit.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="d771kzbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="brandico:box-rect" /></template>
