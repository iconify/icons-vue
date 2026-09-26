<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i3eru1kha.css';
import '../../css/r/r59hdg7vl.css';
import '../../css/c/c73t34bfn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i3eru1kha"/><path class="r59hdg7vl"/><path class="c73t34bfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-image-bold" /></template>
