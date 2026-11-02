<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxfkuffca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxfkuffca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:download-line" /></template>
