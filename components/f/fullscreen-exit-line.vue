<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xhzurs3ve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhzurs3ve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fullscreen-exit-line" /></template>
