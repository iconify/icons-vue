<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cu5xsb1ef.css';
import '../../css/l/l8in5mb0b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7oxRfe1M"><g class="hv130ab-t"><rect class="cu5xsb1ef"/><path class="l8in5mb0b"/></g></mask></defs><path mask="url(#SVG7oxRfe1M)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:alignment-right-center" /></template>
