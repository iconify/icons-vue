<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tsnnjib_v.css';
import '../../css/m/mnr5v1b0o.css';
import '../../css/s/s-c-ff4lw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="tsnnjib_v"/><path clip-rule="evenodd" class="mnr5v1b0o"/><path class="s-c-ff4lw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:globe-americas-bold" /></template>
