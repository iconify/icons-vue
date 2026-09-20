<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4wz7200e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4wz7200e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:coupon-2-fill" /></template>
