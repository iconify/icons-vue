<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp5_a1qwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zp5_a1qwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-diode" /></template>
