<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usb7uf1xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usb7uf1xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:balloon" /></template>
