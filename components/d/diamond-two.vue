<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tu9k0z8qm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAZIpbcqT"><path class="tu9k0z8qm"/></mask></defs><path mask="url(#SVGAZIpbcqT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:diamond-two" /></template>
