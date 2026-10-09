<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkx8hebbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zkx8hebbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:code-2-20-bold" /></template>
