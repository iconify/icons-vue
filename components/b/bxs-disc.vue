<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn3dr3d8s.css';
import '../../css/l/l5yoditpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tn3dr3d8s"/><circle class="l5yoditpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-disc" /></template>
