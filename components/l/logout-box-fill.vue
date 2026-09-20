<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h2_qjfm6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2_qjfm6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:logout-box-fill" /></template>
