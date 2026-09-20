<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq9sayxnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mq9sayxnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:a-arrow-up" /></template>
