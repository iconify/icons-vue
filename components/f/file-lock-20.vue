<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_dv-4xcr.css';
import '../../css/h/hxy_y1dfx.css';
import '../../css/z/z_aw5vbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d_dv-4xcr"/><path class="hxy_y1dfx"/><path class="z_aw5vbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:file-lock-20" /></template>
