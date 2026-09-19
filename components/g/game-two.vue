<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohtjlzb9o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWbHkneAU"><path class="ohtjlzb9o"/></mask></defs><path mask="url(#SVGWbHkneAU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:game-two" /></template>
