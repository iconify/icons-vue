<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znind1bac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znind1bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:fan-fill" /></template>
