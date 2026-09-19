<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdc_7m84r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdc_7m84r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:currency-rupee" /></template>
