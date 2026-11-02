<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/deo_cme6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="deo_cme6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:clock-x-line" /></template>
