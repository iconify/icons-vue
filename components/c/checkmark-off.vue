<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f1c3_hbmh.css';
import '../../css/j/jn_tsyv7z.css';
import '../../css/s/snl4n64vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="f1c3_hbmh"/><path class="jn_tsyv7z"/><path class="snl4n64vp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:checkmark-off" /></template>
