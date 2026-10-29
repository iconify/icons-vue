<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/f/f2i3zrblc.css';
import '../../css/i/ijxc9x4ab.css';
import '../../css/x/xxt23ubae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="f2i3zrblc wm-k"/><path class="ijxc9x4ab"/><path class="wm-s xxt23ubae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:clock-check" /></template>
