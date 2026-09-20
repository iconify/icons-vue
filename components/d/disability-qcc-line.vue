<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh2_t1pnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kh2_t1pnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:disability-qcc-line" /></template>
