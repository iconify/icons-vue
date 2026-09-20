<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlmxcpbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlmxcpbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-z-circle-solid" /></template>
