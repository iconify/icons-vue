<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/fsq5llu2n.css';
import '../../css/t/tvoazbbvq.css';
import '../../css/f/fw-lfobsd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdA4qbe1y"><g class="s9cl3zbei"><path class="fsq5llu2n"/><path class="tvoazbbvq"/><path class="fw-lfobsd"/></g></mask></defs><path mask="url(#SVGdA4qbe1y)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:light-member" /></template>
