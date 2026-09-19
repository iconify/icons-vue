<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqpr4m9dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uqpr4m9dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:btcz" /></template>
