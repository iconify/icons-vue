<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-wx-b4fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h-wx-b4fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:boring" /></template>
