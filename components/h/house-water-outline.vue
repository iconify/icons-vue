<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/c/ceaub_u1f.css';
import '../../css/l/l9lejiboz.css';
import '../../css/d/dpbi1eb5g.css';
import '../../css/h/hwy146b6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="ceaub_u1f"/><path class="l9lejiboz"/><path class="dpbi1eb5g"/><path class="hwy146b6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:house-water-outline" /></template>
