<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nqmqffbvv.css';
import '../../css/q/qmpj-ib3u.css';
import '../../css/d/dytwysbcm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nqmqffbvv"/><path clip-rule="evenodd" class="qmpj-ib3u"/><path class="dytwysbcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gamepad-low-duotone" /></template>
