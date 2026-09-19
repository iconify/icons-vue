<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh2aoccau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="hh2aoccau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-down-circle" /></template>
