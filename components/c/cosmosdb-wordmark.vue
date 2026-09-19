<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmkx4x2wi.css';
import '../../css/k/k79nfqmnv.css';
import '../../css/f/flaemkb3e.css';
import '../../css/h/h2gx32brp.css';
import '../../css/j/jbf8k0x2t.css';
import '../../css/b/bvxxlhroq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="fmkx4x2wi"/><path class="k79nfqmnv"/><path class="flaemkb3e"/><path class="h2gx32brp"/><path class="jbf8k0x2t"/><path class="bvxxlhroq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:cosmosdb-wordmark" /></template>
