<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy--hfb3b.css';
import '../../css/d/dc1zo4nmc.css';
import '../../css/a/a9d8_nbrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jy--hfb3b"/><path class="dc1zo4nmc"/><path class="a9d8_nbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-z-cloud-mod-stack" /></template>
