<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/v/v7o9pdttn.css';
import '../../css/k/kx53vyikr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGv0fEdduZ"><g class="v3_i3wktz"><path class="v7o9pdttn"/><path class="kx53vyikr"/></g></mask></defs><path mask="url(#SVGv0fEdduZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:expand-down" /></template>
