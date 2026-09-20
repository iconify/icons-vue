<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wifg_yb4u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wifg_yb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:barchart" /></template>
