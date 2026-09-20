<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjtkc_n8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjtkc_n8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:coins-minus-outline" /></template>
