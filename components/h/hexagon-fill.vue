<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usb1ve20y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usb1ve20y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:hexagon-fill" /></template>
