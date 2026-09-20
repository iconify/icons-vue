<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8od9obqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h8od9obqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:coffee-cup" /></template>
