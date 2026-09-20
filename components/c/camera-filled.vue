<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2dvr6buw.css';
import '../../css/x/xw7gk0pnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2dvr6buw"/><path class="xw7gk0pnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:camera-filled" /></template>
