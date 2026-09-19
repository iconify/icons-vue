<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wd6_tobvd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wd6_tobvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:block" /></template>
