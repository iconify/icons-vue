<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0c16rc2r.css';
import '../../css/s/se4563bpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0c16rc2r"/><path class="se4563bpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:light-mode-hdr-bold" /></template>
