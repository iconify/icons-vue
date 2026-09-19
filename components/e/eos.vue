<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2eafcbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x2eafcbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:eos" /></template>
