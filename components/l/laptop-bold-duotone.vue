<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n4n_sfbfu.css';
import '../../css/i/i2d4_mb8f.css';
import '../../css/y/ypu22vbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n4n_sfbfu"/><path clip-rule="evenodd" class="i2d4_mb8f"/><path class="ypu22vbic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:laptop-bold-duotone" /></template>
