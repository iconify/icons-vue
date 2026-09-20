<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd9hhcbsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qd9hhcbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:cart-x" /></template>
