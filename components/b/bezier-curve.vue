<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xs28lbcae.css';
import '../../css/a/a9qgo497e.css';
import '../../css/b/b7lc0-bdo.css';
import '../../css/l/lbzqinjha.css';
import '../../css/d/d-kk_6ndx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xs28lbcae"/><path class="a9qgo497e"/><path class="b7lc0-bdo"/><circle class="lbzqinjha"/><circle class="d-kk_6ndx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:bezier-curve" /></template>
