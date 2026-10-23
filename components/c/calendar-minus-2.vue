<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khe5ybbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khe5ybbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:calendar-minus-2" /></template>
