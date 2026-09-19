<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_n7fwc3g.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpLVWObsf"><path class="l_n7fwc3g"/></mask></defs><path mask="url(#SVGpLVWObsf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-vertical-center-two" /></template>
