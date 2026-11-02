<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcy18ybbk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcy18ybbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:heading-fill" /></template>
