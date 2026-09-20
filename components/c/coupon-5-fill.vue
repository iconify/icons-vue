<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kz9_n9bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kz9_n9bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:coupon-5-fill" /></template>
