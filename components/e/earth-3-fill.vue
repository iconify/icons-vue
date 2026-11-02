<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yt4i538vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yt4i538vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:earth-3-fill" /></template>
