<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zftneacjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zftneacjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:alibaba-cloud-fill" /></template>
