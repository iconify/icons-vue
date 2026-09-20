<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnl716bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="nnl716bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:arrow-curvy-up-down-1" /></template>
