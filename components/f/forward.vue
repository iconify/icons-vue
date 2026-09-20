<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq_xre3rx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xq_xre3rx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:forward" /></template>
