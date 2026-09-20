<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdja74b3x.css';
import '../../css/t/tb44rwbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdja74b3x"/><path class="tb44rwbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:data-transfer-edi-reload" /></template>
