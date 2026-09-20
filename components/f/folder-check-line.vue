<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exnl6nbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exnl6nbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-check-line" /></template>
