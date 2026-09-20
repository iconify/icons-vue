<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv6e02qag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv6e02qag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:500px" /></template>
