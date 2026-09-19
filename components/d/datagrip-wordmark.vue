<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxpcccbmp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="dxpcccbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:datagrip-wordmark" /></template>
