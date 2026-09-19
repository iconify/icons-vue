<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s-j_xfees.css';
import '../../css/s/s-45tkb7i.css';
import '../../css/k/ko4cnabae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="s-j_xfees"/><path class="s-45tkb7i"/><path class="ko4cnabae"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:clipboard-heart" /></template>
