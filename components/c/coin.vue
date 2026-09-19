<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vohyy3tlk.css';
import '../../css/m/mj4w1gb3h.css';
import '../../css/a/adgxpsk5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="vohyy3tlk"/><path class="mj4w1gb3h"/><path class="adgxpsk5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:coin" /></template>
