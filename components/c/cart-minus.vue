<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hks7gjbis.css';
import '../../css/z/zsf5lvo7h.css';
import '../../css/w/w9p3ambxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hks7gjbis"/><path class="zsf5lvo7h"/><path clip-rule="evenodd" class="w9p3ambxu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:cart-minus" /></template>
