<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4l58qbls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4l58qbls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-m" /></template>
