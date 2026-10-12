<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znqcvhbmw.css';
import '../../css/x/xmo5rcozs.css';
import '../../css/w/w_5epib3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znqcvhbmw"/><path class="xmo5rcozs"/><path clip-rule="evenodd" class="w_5epib3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:coins-filled" /></template>
