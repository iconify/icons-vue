<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0g_cn3lg.css';
import '../../css/w/waeg4lbhw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d0g_cn3lg"/><path class="waeg4lbhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:df" /></template>
