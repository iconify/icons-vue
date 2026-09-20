<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqd-vimya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqd-vimya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:crop-fill" /></template>
