<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zk_skwi6v.css';
import '../../css/p/pvyxalenk.css';
import '../../css/h/h5_6wb9kx.css';
import '../../css/s/s3-pvbj0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zk_skwi6v"/><path class="pvyxalenk"/><path class="h5_6wb9kx"/><path clip-rule="evenodd" class="s3-pvbj0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-stand-middle-bold" /></template>
