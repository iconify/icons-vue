<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcjrcrbrs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcjrcrbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:big-ben-line" /></template>
