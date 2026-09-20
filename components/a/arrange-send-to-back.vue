<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy-_ygbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy-_ygbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:arrange-send-to-back" /></template>
