<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gza2rb70b.css';
import '../../css/z/zz2o6wb4l.css';
import '../../css/y/ylo_e9tjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gza2rb70b"/><path class="zz2o6wb4l"/><path class="ylo_e9tjc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-large3-duotone" /></template>
