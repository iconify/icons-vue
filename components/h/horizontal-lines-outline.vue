<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pr52f_b5y.css';
import '../../css/c/cba1_qbkr.css';
import '../../css/v/vkca7qppm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="cba1_qbkr"/><path class="vkca7qppm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:horizontal-lines-outline" /></template>
