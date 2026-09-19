<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa-f7x0yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="xa-f7x0yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:hand-left" /></template>
