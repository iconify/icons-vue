<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce4w8bc2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ce4w8bc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:attachment" /></template>
