<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i8s8sughv.css';
import '../../css/u/umh3pebfp.css';
import '../../css/v/vjsd4sbgq.css';
import '../../css/k/kx9parvdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i8s8sughv wm-k"/><path class="umh3pebfp wm-shadow"/><path class="vjsd4sbgq wm-k"/><path class="kx9parvdn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cpu-engrave" /></template>
