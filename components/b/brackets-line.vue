<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbebu2lzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbebu2lzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brackets-line" /></template>
