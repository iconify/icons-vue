<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hmikwmbtn.css';
import '../../css/s/sryxx_bpz.css';
import '../../css/w/wryx67bub.css';
import '../../css/s/s6vgiefch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="hmikwmbtn"/><path clip-rule="evenodd" class="sryxx_bpz"/><path class="wryx67bub"/><path clip-rule="evenodd" class="s6vgiefch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:heart-sparkles-outline" /></template>
