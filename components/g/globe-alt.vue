<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znd8k54cv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znd8k54cv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-alt" /></template>
