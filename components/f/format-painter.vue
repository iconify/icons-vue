<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zf7z3sb0u.css';
import '../../css/o/o_nv49bra.css';
import '../../css/w/wek3qlbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zf7z3sb0u"/><path class="o_nv49bra"/><path class="wek3qlbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:format-painter" /></template>
