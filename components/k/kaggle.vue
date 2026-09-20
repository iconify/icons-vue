<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ko686hmhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ko686hmhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:kaggle" /></template>
