<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrylsobpa.css';
import '../../css/d/dcxj6tbtg.css';
import '../../css/b/bvmkafbrv.css';
import '../../css/k/kk28j3r0s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nrylsobpa"/><path class="dcxj6tbtg"/><path class="bvmkafbrv"/><path class="kk28j3r0s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:hearing" /></template>
