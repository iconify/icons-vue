<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzv4l5-8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzv4l5-8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:facebook-box-fill" /></template>
