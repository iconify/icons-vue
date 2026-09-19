<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m2blynbna.css';
import '../../css/s/sdfja-bqn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRaZNCbTi"><g class="s9cl3zbei"><path class="m2blynbna"/><path class="sdfja-bqn"/></g></mask></defs><path mask="url(#SVGRaZNCbTi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:app-store" /></template>
