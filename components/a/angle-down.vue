<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/v9uxtdtin.css';
import '../../css/p/p3s2lwbxe.css';
import '../../css/m/mo3iz1pxq.css';
import '../../css/c/czpsoimrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="v9uxtdtin"/><path class="p3s2lwbxe"/><path class="mo3iz1pxq"/><path class="czpsoimrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:angle-down" /></template>
