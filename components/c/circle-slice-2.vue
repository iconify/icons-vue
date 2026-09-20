<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjrq__szk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjrq__szk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:circle-slice-2" /></template>
