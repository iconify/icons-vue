<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o2cef4b8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o2cef4b8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:fresh-juice" /></template>
