<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxgi9p8-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxgi9p8-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:corner-down-right-solid" /></template>
