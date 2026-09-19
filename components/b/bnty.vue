<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9r0jm58k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d9r0jm58k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:bnty" /></template>
