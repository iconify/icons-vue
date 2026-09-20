<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fa7nocbur.css';
import '../../css/p/p39k-2awn.css';
import '../../css/s/sy-bnbbuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fa7nocbur"/><path class="p39k-2awn"/><path class="sy-bnbbuw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:image-search" /></template>
