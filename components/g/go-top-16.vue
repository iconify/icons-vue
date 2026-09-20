<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znnm_ubqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="znnm_ubqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:go-top-16" /></template>
