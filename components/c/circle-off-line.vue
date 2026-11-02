<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xsl-0tizg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsl-0tizg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:circle-off-line" /></template>
