<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oxpdmv6kz.css';
import '../../css/x/xug629bwe.css';
import '../../css/a/a-nja-bsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oxpdmv6kz"/><path clip-rule="evenodd" class="xug629bwe"/><path class="a-nja-bsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:command-duotone" /></template>
