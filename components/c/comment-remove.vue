<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/davbkx99a.css';
import '../../css/o/o_kyyrbhe.css';
import '../../css/b/bjwr08bib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="davbkx99a"/><path class="o_kyyrbhe"/><path class="bjwr08bib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:comment-remove" /></template>
