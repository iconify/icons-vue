<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/um34ubtfl.css';
import '../../css/o/odpe3tbca.css';
import '../../css/i/iostzby_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="um34ubtfl"/><path class="odpe3tbca"/><path class="iostzby_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:floppy-disk" /></template>
