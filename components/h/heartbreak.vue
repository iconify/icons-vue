<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/r/r9nf2_wsj.css';
import '../../css/a/aag3kl4wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="r9nf2_wsj"/><path class="aag3kl4wn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:heartbreak" /></template>
