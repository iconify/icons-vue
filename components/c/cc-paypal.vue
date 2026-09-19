<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn32y0v_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="vn32y0v_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:cc-paypal" /></template>
