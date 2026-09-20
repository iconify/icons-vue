<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qptdhcbdl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qptdhcbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-2-line" /></template>
