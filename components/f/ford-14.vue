<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkl-9wbbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="mkl-9wbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:ford-14" /></template>
