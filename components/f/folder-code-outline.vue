<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt07y0bxu.css';
import '../../css/y/y1r440bhs.css';
import '../../css/m/mxpx_sbmx.css';
import '../../css/p/pzmtr-buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt07y0bxu"/><path class="y1r440bhs"/><path class="mxpx_sbmx"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-code-outline" /></template>
