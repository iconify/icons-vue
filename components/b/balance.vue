<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsfne-b7l.css';
import '../../css/y/y5_j5gb1z.css';
import '../../css/j/jzt70vrgh.css';
import '../../css/u/upmnh4bil.css';
import '../../css/j/jnqfbr3zy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYlnBddjq"><g class="nsfne-b7l"><path class="y5_j5gb1z"/><path class="jzt70vrgh"/><path class="upmnh4bil"/><path class="jnqfbr3zy"/></g></mask></defs><path mask="url(#SVGYlnBddjq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:balance" /></template>
