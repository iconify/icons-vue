<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntd0jsay.css';
import '../../css/l/l7rj5bayp.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/s/s5v8bubiv.css';
import '../../css/h/hsr133bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="hntd0jsay"/><path class="l7rj5bayp"/><g class="jn8qy4bru"><path class="s5v8bubiv"/><path class="hsr133bia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:diamond-with-a-dot" /></template>
