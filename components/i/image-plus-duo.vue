<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xgfh04b0u.css';
import '../../css/f/fvp0h1bsk.css';
import '../../css/m/miknsv_yb.css';
import '../../css/a/ain1tnbxt.css';
import '../../css/s/sy7kpcbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="xgfh04b0u"/><path class="fvp0h1bsk wm-s"/><path class="miknsv_yb wm-s"/><path class="ain1tnbxt"/><path class="sy7kpcbuo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:image-plus-duo" /></template>
