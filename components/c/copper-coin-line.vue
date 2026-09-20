<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inr7twbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inr7twbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:copper-coin-line" /></template>
