<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7i07eb_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7i07eb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:coupon-fill" /></template>
