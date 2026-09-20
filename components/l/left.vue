<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyc-mbcsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="yyc-mbcsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:left" /></template>
