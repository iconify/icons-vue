<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wuh36-brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="wuh36-brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:hand-grab" /></template>
