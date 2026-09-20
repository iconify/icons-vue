<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggrv6-bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggrv6-bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:danmaku-line" /></template>
