<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/in1dviszv.css';
import '../../css/k/k5m2if1qz.css';
import '../../css/w/wgz_qwbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="in1dviszv"><path class="k5m2if1qz"/><path class="wgz_qwbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:discover" /></template>
