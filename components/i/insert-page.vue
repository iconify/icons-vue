<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thh54cc_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="thh54cc_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:insert-page" /></template>
