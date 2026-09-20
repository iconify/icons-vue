<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9kw68b_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9kw68b_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-e-circle-solid" /></template>
