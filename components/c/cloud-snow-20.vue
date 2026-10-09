<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af023dsnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="af023dsnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloud-snow-20" /></template>
