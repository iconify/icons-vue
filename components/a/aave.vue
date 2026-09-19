<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqlzmjd_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xqlzmjd_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:aave" /></template>
