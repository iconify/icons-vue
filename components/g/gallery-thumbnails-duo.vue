<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zx2d8wbyd.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wrj87acev.css';
import '../../css/n/n8-7hlbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zx2d8wbyd"/><g class="dt0cm9dhy primary"><path class="wrj87acev"/><path class="n8-7hlbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:gallery-thumbnails-duo" /></template>
