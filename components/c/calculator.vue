<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xiyunvb8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xiyunvb8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:calculator" /></template>
