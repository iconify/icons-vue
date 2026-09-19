<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jl81vn0ac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jl81vn0ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:black-circle" /></template>
