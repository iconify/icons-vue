<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp7yrqrxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp7yrqrxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:gift-line" /></template>
