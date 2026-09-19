<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0-mlhn1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o0-mlhn1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:btc" /></template>
