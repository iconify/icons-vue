<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyh2a17xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyh2a17xs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:flexibility-line" /></template>
