<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rtdqotsqn.css';
import '../../css/s/sryg2hb0f.css';
import '../../css/l/lmj6xn97l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rtdqotsqn"/><path class="sryg2hb0f"/><path clip-rule="evenodd" class="lmj6xn97l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-circle-bold-duotone" /></template>
