<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o0ebj98gu.css';
import '../../css/j/jlin40zen.css';
import '../../css/n/nglwwbzdo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiChrWclO"><g class="ft5dv1b6b"><path class="o0ebj98gu"/><path class="jlin40zen"/><path class="nglwwbzdo"/></g></mask></defs><path mask="url(#SVGiChrWclO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:doc-search-two" /></template>
