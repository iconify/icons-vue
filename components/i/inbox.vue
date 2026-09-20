<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgtg07bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="xgtg07bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:inbox" /></template>
