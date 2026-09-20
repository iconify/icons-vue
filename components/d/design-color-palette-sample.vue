<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl8i0-bnz.css';
import '../../css/c/cnn8c6pbg.css';
import '../../css/d/donjoukqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zl8i0-bnz"/><path class="cnn8c6pbg"/><path class="donjoukqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-color-palette-sample" /></template>
