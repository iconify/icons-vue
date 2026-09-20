<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti44f9bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti44f9bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:coupon-3-line" /></template>
