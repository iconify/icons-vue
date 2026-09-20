<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkr-y0bjo.css';
import '../../css/p/pfpnh2nsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lkr-y0bjo"/><path class="pfpnh2nsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:book-ltr" /></template>
