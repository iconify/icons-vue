<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbpay4bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbpay4bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chevron-down-to-line-fill-round" /></template>
