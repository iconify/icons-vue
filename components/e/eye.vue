<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx6vq2bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="tx6vq2bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:eye" /></template>
