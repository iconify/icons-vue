<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vq_xz2nmb.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/f/fh1mgzuzo.css';
import '../../css/s/s2p8flb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="vq_xz2nmb"/><g class="mc2zb0bvp"><path class="fh1mgzuzo"/><path class="s2p8flb5p"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:forward-bold-duotone" /></template>
