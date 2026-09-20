<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ou4l32ycl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ou4l32ycl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:call-remove-filled" /></template>
