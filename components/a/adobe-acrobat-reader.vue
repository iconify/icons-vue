<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-gonbb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w-gonbb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:adobe-acrobat-reader" /></template>
