<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zam2drdnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zam2drdnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-minus" /></template>
