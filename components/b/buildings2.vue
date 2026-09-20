<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7fmnlb4r.css';
import '../../css/i/ifroi7b3s.css';
import '../../css/l/llfe_abfd.css';
import '../../css/u/utsg_1-6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="ifroi7b3s"/><path class="llfe_abfd"/><path class="utsg_1-6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:buildings2" /></template>
