<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi8xxdwkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fi8xxdwkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fries-filled" /></template>
