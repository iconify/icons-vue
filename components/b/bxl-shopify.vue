<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob8f3hzgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob8f3hzgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-shopify" /></template>
