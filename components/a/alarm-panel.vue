<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp5rksb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp5rksb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:alarm-panel" /></template>
