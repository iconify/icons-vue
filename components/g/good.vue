<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs3tzmb_z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGD7akPb4b"><path class="fs3tzmb_z"/></mask></defs><path mask="url(#SVGD7akPb4b)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:good" /></template>
