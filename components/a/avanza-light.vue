<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1sukl-mj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1549,"height":1881};
const content = `<path class="f1sukl-mj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:avanza-light" /></template>
