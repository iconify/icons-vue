<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/b/bt97avbye.css';
import '../../css/w/wdtytfyie.css';
import '../../css/r/r045luk3o.css';
import '../../css/j/jftmc7bxv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNJJcMcWx"><g class="ufeehvblu"><path class="bt97avbye"/><path class="wdtytfyie"/><path class="r045luk3o"/><path class="jftmc7bxv"/></g></mask></defs><path mask="url(#SVGNJJcMcWx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:hourglass-full" /></template>
