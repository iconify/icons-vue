<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucwpi1bge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ucwpi1bge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:line-horizontal-3-decrease" /></template>
