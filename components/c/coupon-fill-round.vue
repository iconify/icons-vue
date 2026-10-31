<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7spb4buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7spb4buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coupon-fill-round" /></template>
