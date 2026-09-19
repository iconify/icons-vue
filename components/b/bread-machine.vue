<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohhhzb0l.css';
import '../../css/d/drtx_1_li.css';
import '../../css/k/kbmf7zbig.css';
import '../../css/x/xqa4lusgk.css';
import '../../css/z/zkqbqgb3y.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHyhwDbKS"><g class="rohhhzb0l"><path class="drtx_1_li"/><path class="kbmf7zbig"/><circle class="xqa4lusgk"/><path class="zkqbqgb3y"/></g></mask></defs><path mask="url(#SVGHyhwDbKS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bread-machine" /></template>
