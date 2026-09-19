<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjd_3-boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xjd_3-boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:cc-paypal" /></template>
