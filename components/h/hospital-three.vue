<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l-piu6bto.css';
import '../../css/n/nlpt91dtk.css';
import '../../css/w/wpk5h2bgb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGekCfQbmp"><g class="ft5dv1b6b"><path class="l-piu6bto"/><path class="nlpt91dtk"/><path class="wpk5h2bgb"/></g></mask></defs><path mask="url(#SVGekCfQbmp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hospital-three" /></template>
