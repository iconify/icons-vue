<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dc6_e3_dl.css';
import '../../css/z/zlmt_sszd.css';
import '../../css/y/y0qmgo4nn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGceNnccAT"><g class="v3_i3wktz"><path class="dc6_e3_dl"/><path class="zlmt_sszd"/><path class="y0qmgo4nn"/></g></mask></defs><path mask="url(#SVGceNnccAT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:list-top" /></template>
