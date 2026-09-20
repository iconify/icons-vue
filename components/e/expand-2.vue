<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl_5e3bdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl_5e3bdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:expand-2" /></template>
