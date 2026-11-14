<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hhzocojuh.css';
import '../../css/i/i5thibbft.css';
import '../../css/c/c44m2o2uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hhzocojuh"/><path class="i5thibbft"/><path class="c44m2o2uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:file-axis-3d" /></template>
