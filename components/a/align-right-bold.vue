<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/frcyxfb_h.css';
import '../../css/u/u1biqstsa.css';
import '../../css/g/grad3z_os.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="frcyxfb_h"/><path class="u1biqstsa"/><path class="grad3z_os"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-right-bold" /></template>
