<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubs1v_4lx.css';
import '../../css/d/dxhdilb2v.css';
import '../../css/g/g4y8tubxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ubs1v_4lx"/><path class="dxhdilb2v"/><path class="g4y8tubxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gryt-light" /></template>
