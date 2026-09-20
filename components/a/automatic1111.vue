<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmt_-3gzv.css';
import '../../css/l/l-3emlabv.css';
import '../../css/u/uv73q-b-l.css';
import '../../css/y/ypernbbma.css';
import '../../css/c/cg0iy4byq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gmt_-3gzv"/><path class="l-3emlabv"/><path class="uv73q-b-l"/><path class="ypernbbma"/><path class="cg0iy4byq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:automatic1111" /></template>
