<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gea7pzbuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gea7pzbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:helmet" /></template>
