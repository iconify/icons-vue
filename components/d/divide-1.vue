<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boyb725ez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="boyb725ez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:divide-1" /></template>
