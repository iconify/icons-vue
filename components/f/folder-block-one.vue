<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/h/h744_ccdj.css';
import '../../css/p/p40iu0bgs.css';
import '../../css/k/kc38scbvr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGN0NSScNY"><g class="s9cl3zbei"><path class="h744_ccdj"/><circle class="p40iu0bgs"/><path class="kc38scbvr"/></g></mask></defs><path mask="url(#SVGN0NSScNY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:folder-block-one" /></template>
