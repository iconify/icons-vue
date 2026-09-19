<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-l1pd0_w.css';
import '../../css/t/troua1bdv.css';
import '../../css/g/gt458lbgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h-l1pd0_w"><path clip-rule="evenodd" class="troua1bdv"/><path class="gt458lbgp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:keyframes-couple-solid" /></template>
