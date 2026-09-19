<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kj7uwmfyr.css';
import '../../css/h/hlp0kabjt.css';
import '../../css/e/egneazb5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="kj7uwmfyr"/><path class="hlp0kabjt"/><path class="egneazb5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:file-checkmark" /></template>
