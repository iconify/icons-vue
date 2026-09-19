<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-gm7ibvs.css';
import '../../css/m/mzy1pxb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-gm7ibvs"/><path class="mzy1pxb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-bitcoin" /></template>
