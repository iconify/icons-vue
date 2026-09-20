<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yyb2bbcoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yyb2bbcoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:fx-16" /></template>
