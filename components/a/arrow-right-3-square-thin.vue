<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mk9pm4lzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mk9pm4lzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-3-square-thin" /></template>
