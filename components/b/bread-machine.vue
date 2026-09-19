<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/h/hgvt_xb0r.css';
import '../../css/k/kedy5fgog.css';
import '../../css/z/zi97iu6ok.css';
import '../../css/y/ye5r-gvlj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKfOF1dtE"><g class="s9cl3zbei"><path class="hgvt_xb0r"/><path class="kedy5fgog"/><circle class="zi97iu6ok"/><path class="ye5r-gvlj"/></g></mask></defs><path mask="url(#SVGKfOF1dtE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bread-machine" /></template>
