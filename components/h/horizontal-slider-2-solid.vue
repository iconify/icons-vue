<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ea3wjl-2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ea3wjl-2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:horizontal-slider-2-solid" /></template>
