<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lnt3u0v0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnt3u0v0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grip-horizontal" /></template>
