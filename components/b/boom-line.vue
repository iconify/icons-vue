<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dv_0-d7tj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dv_0-d7tj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:boom-line" /></template>
