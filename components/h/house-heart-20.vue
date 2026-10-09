<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpx9c7b2s.css';
import '../../css/d/dw6_5lnpc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rpx9c7b2s"/><path class="dw6_5lnpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-heart-20" /></template>
