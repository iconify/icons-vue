<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu3t0ac_w.css';
import '../../css/u/uobch0qxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu3t0ac_w"/><path class="uobch0qxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:color-spray" /></template>
