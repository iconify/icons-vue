<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwm8u_t-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwm8u_t-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:align-bottom" /></template>
