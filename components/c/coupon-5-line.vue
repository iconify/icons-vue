<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj3_8nbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj3_8nbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:coupon-5-line" /></template>
