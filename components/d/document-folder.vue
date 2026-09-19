<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/eg_wvsb4d.css';
import '../../css/f/f0ql7tbff.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGa0DOTdgy"><g class="v3_i3wktz"><path class="eg_wvsb4d"/><path class="f0ql7tbff"/></g></mask></defs><path mask="url(#SVGa0DOTdgy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:document-folder" /></template>
