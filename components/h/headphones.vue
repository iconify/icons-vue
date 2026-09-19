<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpn0tfite.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1408};
const content = `<path class="dpn0tfite"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:headphones" /></template>
