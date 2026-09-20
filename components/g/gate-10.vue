<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xnnov91gx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":10};
const content = `<path class="xnnov91gx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:gate-10" /></template>
