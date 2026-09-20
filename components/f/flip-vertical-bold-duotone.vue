<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/o/oc2k35lmh.css';
import '../../css/e/epjv0pbmv.css';
import '../../css/y/yr-jb4bim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="oc2k35lmh"/><path class="epjv0pbmv"/></g><path clip-rule="evenodd" class="yr-jb4bim"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-vertical-bold-duotone" /></template>
