<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/z/zsmadgbrk.css';
import '../../css/r/ra83ujb3l.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwSXmnKKa"><g class="v3_i3wktz"><path class="zsmadgbrk"/><path class="ra83ujb3l"/></g></mask></defs><path mask="url(#SVGwSXmnKKa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:distribute-vertically" /></template>
