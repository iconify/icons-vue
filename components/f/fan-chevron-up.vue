<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjbdo-_2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjbdo-_2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fan-chevron-up" /></template>
