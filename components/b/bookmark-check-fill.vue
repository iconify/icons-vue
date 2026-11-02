<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbmj_suox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qbmj_suox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bookmark-check-fill" /></template>
