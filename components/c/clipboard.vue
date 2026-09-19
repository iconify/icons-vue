<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bf-knybbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf-knybbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:clipboard" /></template>
