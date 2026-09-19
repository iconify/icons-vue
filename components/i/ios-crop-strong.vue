<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yigoh0b8f.css';
import '../../css/h/hoth7qk6d.css';
import '../../css/x/xgk3jto0j.css';
import '../../css/l/ld7eseqtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yigoh0b8f"/><path class="hoth7qk6d"/><path class="xgk3jto0j"/><path class="ld7eseqtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-crop-strong" /></template>
