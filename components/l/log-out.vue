<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enuv-esbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enuv-esbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:log-out" /></template>
