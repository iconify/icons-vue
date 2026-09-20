<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5c5z8huf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5c5z8huf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:logout-box-r-fill" /></template>
