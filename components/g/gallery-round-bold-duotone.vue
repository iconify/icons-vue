<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c0tsxrhtd.css';
import '../../css/u/uafzi8bgb.css';
import '../../css/y/y_8irlb1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c0tsxrhtd"/><path clip-rule="evenodd" class="uafzi8bgb"/><path class="y_8irlb1x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-round-bold-duotone" /></template>
