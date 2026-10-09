<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pn86m-bcf.css';
import '../../css/v/vvf4d-dpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pn86m-bcf"/><path class="vvf4d-dpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:mail-20-bold" /></template>
