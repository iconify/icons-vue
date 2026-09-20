<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqkj8vciz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqkj8vciz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bookmark-check" /></template>
