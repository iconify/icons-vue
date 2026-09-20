<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntvn5jw-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ntvn5jw-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:dailymotion-logo-block" /></template>
