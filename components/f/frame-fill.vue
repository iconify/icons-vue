<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5-v0tbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5-v0tbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:frame-fill" /></template>
