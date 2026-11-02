<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tv_yzke7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv_yzke7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-slash-2-line" /></template>
