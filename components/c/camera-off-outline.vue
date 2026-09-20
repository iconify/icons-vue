<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/whwf_s5on.css';
import '../../css/o/op-uyebei.css';
import '../../css/c/c0q-ydf9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="whwf_s5on"/><path class="op-uyebei"/><path class="c0q-ydf9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:camera-off-outline" /></template>
