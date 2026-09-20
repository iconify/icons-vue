<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxr4rcbqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zxr4rcbqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:angle-up-solid" /></template>
