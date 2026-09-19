<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy_rrbc-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cy_rrbc-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:hot" /></template>
