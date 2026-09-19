<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk8ct-eui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vk8ct-eui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:creative-commons-sampling" /></template>
