<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/asoc6abfb.css';
import '../../css/b/b8uc8qb-p.css';
import '../../css/r/refo3vb5p.css';
import '../../css/z/z5wo1fb-k.css';
import '../../css/b/biqbl5nrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="asoc6abfb"/><path class="b8uc8qb-p"/><path class="refo3vb5p"/><path clip-rule="evenodd" class="z5wo1fb-k"/><path clip-rule="evenodd" class="biqbl5nrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:globe-stand-1" /></template>
