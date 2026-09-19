<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j0uu7sblb.css';
import '../../css/j/jx9zyu03l.css';
import '../../css/o/o4ej_lc-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="j0uu7sblb"/><path class="jx9zyu03l"/><circle class="o4ej_lc-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:comment-1" /></template>
