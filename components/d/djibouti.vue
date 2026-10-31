<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6fla5ihq.css';
import '../../css/w/wc3ev5p3f.css';
import '../../css/k/k6f9ajnvk.css';
import '../../css/f/fy2k2g21h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="q6fla5ihq"/><path class="wc3ev5p3f"/><path class="k6f9ajnvk"/><path class="fy2k2g21h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:djibouti" /></template>
