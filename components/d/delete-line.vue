<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xjgk6__av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xjgk6__av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:delete-line" /></template>
