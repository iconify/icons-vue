<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4xwqdi_h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4xwqdi_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-500px" /></template>
