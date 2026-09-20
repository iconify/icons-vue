<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_xa14bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w_xa14bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cursor-2-fill" /></template>
