<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blnz3vcsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="blnz3vcsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:energy-cooperative-20-bold" /></template>
