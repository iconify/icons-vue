<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/noh6rfbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="noh6rfbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:cannon" /></template>
