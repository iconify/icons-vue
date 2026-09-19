<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck_pfnhtq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ck_pfnhtq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency-baht" /></template>
