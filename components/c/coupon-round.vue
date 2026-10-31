<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g84rt4bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g84rt4bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:coupon-round" /></template>
