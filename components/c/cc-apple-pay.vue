<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp4ber88j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zp4ber88j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cc-apple-pay" /></template>
