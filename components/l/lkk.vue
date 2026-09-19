<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o06v5dbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o06v5dbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:lkk" /></template>
