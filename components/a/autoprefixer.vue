<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvv8gtn1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fvv8gtn1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:autoprefixer" /></template>
