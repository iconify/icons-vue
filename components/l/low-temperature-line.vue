<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrcs06bmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrcs06bmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:low-temperature-line" /></template>
