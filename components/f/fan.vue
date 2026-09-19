<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_o9s2byh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="h_o9s2byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:fan" /></template>
