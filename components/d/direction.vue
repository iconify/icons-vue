<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fbxmsfbue.css';
import '../../css/w/w17uzvbov.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFpN5cc0d"><g class="ft5dv1b6b"><rect class="fbxmsfbue"/><path class="w17uzvbov"/></g></mask></defs><path mask="url(#SVGFpN5cc0d)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:direction" /></template>
