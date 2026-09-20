<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz2q7telr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz2q7telr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-right-down-fill" /></template>
