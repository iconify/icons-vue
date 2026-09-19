<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6srddc_x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkvkc1cLV"><path class="d6srddc_x"/></mask></defs><path mask="url(#SVGkvkc1cLV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:game-emoji" /></template>
