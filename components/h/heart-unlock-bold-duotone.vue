<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/z/zs6l8u0uh.css';
import '../../css/g/gdoe5tb6n.css';
import '../../css/k/k0nbc90lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zs6l8u0uh"/><path class="gdoe5tb6n"/><path clip-rule="evenodd" class="k0nbc90lp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:heart-unlock-bold-duotone" /></template>
