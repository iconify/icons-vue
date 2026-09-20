<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hl659uogt.css';
import '../../css/x/xi0wytc-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<g class="cuyn6tgcc"><path class="hl659uogt"/><path class="xi0wytc-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iwwa:file-pdf" /></template>
