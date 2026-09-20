<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-r2acsdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="z-r2acsdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:earth-airplane-remix" /></template>
