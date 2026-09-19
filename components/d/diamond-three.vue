<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rh5my5ilm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1xKdadUH"><path class="rh5my5ilm"/></mask></defs><path mask="url(#SVG1xKdadUH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:diamond-three" /></template>
