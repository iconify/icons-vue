<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1cb0d2jl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b1cb0d2jl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:entrp" /></template>
