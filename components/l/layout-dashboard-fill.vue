<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wctd4xbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wctd4xbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:layout-dashboard-fill" /></template>
