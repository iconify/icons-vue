<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8nmdtboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s8nmdtboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:cs" /></template>
