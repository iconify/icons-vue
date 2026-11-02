<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsok2thnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsok2thnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-remove-fill" /></template>
