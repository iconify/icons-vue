<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/f694ycdso.css';
import '../../css/z/z3m924b_g.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcZLgRdnM"><g class="v3_i3wktz"><path class="f694ycdso"/><path class="z3m924b_g"/></g></mask></defs><path mask="url(#SVGcZLgRdnM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:expand-left" /></template>
