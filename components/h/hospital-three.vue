<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xcl5w9i1i.css';
import '../../css/n/nlpt91dtk.css';
import '../../css/k/ki6cgacny.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGntpdGe7a"><g class="ft5dv1b6b"><path class="xcl5w9i1i"/><path class="nlpt91dtk"/><path class="ki6cgacny"/></g></mask></defs><path mask="url(#SVGntpdGe7a)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hospital-three" /></template>
