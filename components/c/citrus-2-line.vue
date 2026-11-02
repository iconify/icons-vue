<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tefh-wl-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tefh-wl-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:citrus-2-line" /></template>
