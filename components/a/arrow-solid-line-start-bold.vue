<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dce5w2b3k.css';
import '../../css/r/rj0_dwbpf.css';
import '../../css/f/f4dci94xs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="dce5w2b3k"/><path class="rj0_dwbpf"/><path class="f4dci94xs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-line-start-bold" /></template>
