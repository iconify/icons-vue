<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b1w3jxbdi.css';
import '../../css/n/n3xmixbkr.css';
import '../../css/n/nvixmrbwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b1w3jxbdi"/><path clip-rule="evenodd" class="n3xmixbkr"/><path class="nvixmrbwm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cpu-bolt-duotone" /></template>
