<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncyrnks2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncyrnks2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-2-line" /></template>
