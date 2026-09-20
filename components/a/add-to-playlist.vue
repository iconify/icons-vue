<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlfft2byz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wlfft2byz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:add-to-playlist" /></template>
