<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o52m7dbbd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgUj2T2pb"><path class="o52m7dbbd"/></mask></defs><path mask="url(#SVGgUj2T2pb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:block-four" /></template>
