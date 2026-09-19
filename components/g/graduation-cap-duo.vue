<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p4y92abcd.css';
import '../../css/z/zusr_mb9w.css';
import '../../css/t/tf5ukcbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="p4y92abcd"/><path class="zusr_mb9w"/><path class="tf5ukcbuf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:graduation-cap-duo" /></template>
