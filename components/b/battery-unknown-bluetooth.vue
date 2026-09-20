<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1xoq1bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1xoq1bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-unknown-bluetooth" /></template>
