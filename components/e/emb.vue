<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dezzay_1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dezzay_1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:emb" /></template>
