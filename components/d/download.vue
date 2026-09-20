<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h02zmjtek.css';
import '../../css/x/xk9upfb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="h02zmjtek"/><path class="xk9upfb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:download" /></template>
