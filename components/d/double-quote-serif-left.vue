<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zizo1ybwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="zizo1ybwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:double-quote-serif-left" /></template>
