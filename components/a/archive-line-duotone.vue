<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/skui-0bnl.css';
import '../../css/o/ohl_stbmh.css';
import '../../css/w/wz6jt76ak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="skui-0bnl"/><path class="ohl_stbmh"/><path class="wz6jt76ak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:archive-line-duotone" /></template>
