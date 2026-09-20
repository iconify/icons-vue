<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcho64smd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcho64smd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:haze-solid" /></template>
