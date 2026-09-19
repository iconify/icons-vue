<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quy6tdbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quy6tdbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:coupon" /></template>
