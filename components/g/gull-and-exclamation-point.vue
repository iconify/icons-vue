<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tsovqt3vk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="tsovqt3vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gull-and-exclamation-point" /></template>
