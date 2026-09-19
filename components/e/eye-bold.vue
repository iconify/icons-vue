<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p4kgap47f.css';
import '../../css/k/ka8w_gbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="p4kgap47f"/><path clip-rule="evenodd" class="ka8w_gbvw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:eye-bold" /></template>
