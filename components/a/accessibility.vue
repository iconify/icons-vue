<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoaf3-v2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoaf3-v2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:accessibility" /></template>
