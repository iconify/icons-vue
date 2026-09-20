<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsl8n1rvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zsl8n1rvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bootstrap-line" /></template>
