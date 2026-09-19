<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twbw68b_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twbw68b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:doctor-24px" /></template>
