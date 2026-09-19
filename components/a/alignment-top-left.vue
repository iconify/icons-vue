<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/c/cu5xsb1ef.css';
import '../../css/d/d-t4_bc_b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZTwDxbPX"><g class="hv130ab-t"><rect class="cu5xsb1ef"/><path class="d-t4_bc_b"/></g></mask></defs><path mask="url(#SVGZTwDxbPX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:alignment-top-left" /></template>
