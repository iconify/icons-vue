<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xyxr4_bcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xyxr4_bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:align-letter-right" /></template>
