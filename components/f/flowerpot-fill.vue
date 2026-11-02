<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xljhjfbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xljhjfbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flowerpot-fill" /></template>
