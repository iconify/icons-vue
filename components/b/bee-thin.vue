<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izn1bdsiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="izn1bdsiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bee-thin" /></template>
