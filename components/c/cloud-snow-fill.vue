<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fzs9y6jfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="fzs9y6jfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-snow-fill" /></template>
