<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt8_cobrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zt8_cobrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-activated-filled" /></template>
