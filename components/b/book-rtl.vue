<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwbsocnoy.css';
import '../../css/p/pfpnh2nsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xwbsocnoy"/><path class="pfpnh2nsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:book-rtl" /></template>
