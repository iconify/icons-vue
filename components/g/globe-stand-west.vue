<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k8ge1bcui.css';
import '../../css/q/qv378zb_o.css';
import '../../css/b/bs2h29ckb.css';
import '../../css/z/zd-v1bcen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="k8ge1bcui"/><path class="qv378zb_o"/><path class="bs2h29ckb"/><path clip-rule="evenodd" class="zd-v1bcen"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:globe-stand-west" /></template>
