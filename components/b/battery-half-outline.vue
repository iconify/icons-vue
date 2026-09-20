<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/swy3tebjf.css';
import '../../css/e/e5m4qbbih.css';
import '../../css/b/bku0ur4-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="swy3tebjf"/><path class="e5m4qbbih"/><path clip-rule="evenodd" class="bku0ur4-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:battery-half-outline" /></template>
