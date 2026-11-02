<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmxptabih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmxptabih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:book-down-fill" /></template>
