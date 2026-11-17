<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf78fhlzv.css';
import '../../css/t/tvyzckmsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="kf78fhlzv"/><path class="tvyzckmsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:doska" /></template>
