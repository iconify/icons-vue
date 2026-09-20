<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtge1ybso.css';
import '../../css/u/ujy_e8uzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vtge1ybso"/><path class="ujy_e8uzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:hand-like" /></template>
