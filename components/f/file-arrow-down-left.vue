<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mdbfn1bya.css';
import '../../css/m/mlyzuub0m.css';
import '../../css/e/egneazb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="mdbfn1bya"/><path class="mlyzuub0m"/><path class="egneazb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:file-arrow-down-left" /></template>
