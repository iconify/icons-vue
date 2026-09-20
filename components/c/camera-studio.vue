<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkm14zb_u.css';
import '../../css/e/emrf_55ka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkm14zb_u"/><path class="emrf_55ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:camera-studio" /></template>
