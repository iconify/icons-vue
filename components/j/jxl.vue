<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpfxbv8_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="jpfxbv8_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:jxl" /></template>
