<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdwzq1_al.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdwzq1_al"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:book-check" /></template>
