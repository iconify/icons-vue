<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wk3i3-mbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wk3i3-mbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:books-14" /></template>
