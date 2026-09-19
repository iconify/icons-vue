<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xw0_rhs8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1536};
const content = `<path class="xw0_rhs8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:cc-paypal" /></template>
