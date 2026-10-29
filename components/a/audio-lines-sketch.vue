<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rkuqwcccv.css';
import '../../css/o/ocm4x3bst.css';
import '../../css/y/ypm8tacew.css';
import '../../css/k/khxq59b4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rkuqwcccv wm-k"/><path class="ocm4x3bst wm-a"/><path class="wm-k ypm8tacew"/><path class="khxq59b4x wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:audio-lines-sketch" /></template>
