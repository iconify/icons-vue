<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt_o8x1wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt_o8x1wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:forwardburger" /></template>
