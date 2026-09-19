<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yaxhd4e-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="yaxhd4e-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:file-word" /></template>
