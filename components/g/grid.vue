<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aj5gz5b0j.css';
import '../../css/t/tontn-b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":31,"height":32};
const content = `<g class="cuyn6tgcc"><path class="aj5gz5b0j"/><path class="tontn-b1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="et:grid" /></template>
