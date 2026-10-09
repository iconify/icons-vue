<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti32esbih.css';
import '../../css/w/wj5v6jccx.css';
import '../../css/p/pkn8zcbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ti32esbih"/><path class="wj5v6jccx"/><path class="pkn8zcbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:fingerprint-20-bold" /></template>
