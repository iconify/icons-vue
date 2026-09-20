<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yltwzsuot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yltwzsuot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:bluetooth" /></template>
