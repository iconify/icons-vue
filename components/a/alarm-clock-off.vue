<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ca5_w8bkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ca5_w8bkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:alarm-clock-off" /></template>
