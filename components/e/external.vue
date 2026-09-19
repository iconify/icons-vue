<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml1d8i_dw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ml1d8i_dw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:external" /></template>
