<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gdj5xab5v.css';
import '../../css/x/xe-aa8nas.css';
import '../../css/e/egneazb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="gdj5xab5v"/><path class="xe-aa8nas"/><path class="egneazb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:file-plus" /></template>
