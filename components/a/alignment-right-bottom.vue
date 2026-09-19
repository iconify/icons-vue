<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gopnm44um.css';
import '../../css/i/i5p4ugbzq.css';
import '../../css/r/rs1p7xb2g.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGiW9ioeTP"><g class="gopnm44um"><rect class="i5p4ugbzq"/><path class="rs1p7xb2g"/></g></mask></defs><path mask="url(#SVGiW9ioeTP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:alignment-right-bottom" /></template>
