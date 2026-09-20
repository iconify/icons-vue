<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9tr6bcfx.css';
import '../../css/d/d8jjj50pd.css';
import '../../css/g/grn_1v_6f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="d8jjj50pd"/><path class="grn_1v_6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:camera-tripod" /></template>
