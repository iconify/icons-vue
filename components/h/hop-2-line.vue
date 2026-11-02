<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwue91e1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwue91e1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hop-2-line" /></template>
