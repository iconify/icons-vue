<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adexpl72i.css';
import '../../css/b/bshyy_b6k.css';
import '../../css/a/a358q0xfm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIMeHvGGe"><g class="adexpl72i"><circle class="bshyy_b6k"/><path class="a358q0xfm"/></g></mask></defs><path mask="url(#SVGIMeHvGGe)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:boy-one" /></template>
