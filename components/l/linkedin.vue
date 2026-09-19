<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpzgadc_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="hpzgadc_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:linkedin" /></template>
