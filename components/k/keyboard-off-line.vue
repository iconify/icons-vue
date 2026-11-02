<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yicd53btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yicd53btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:keyboard-off-line" /></template>
