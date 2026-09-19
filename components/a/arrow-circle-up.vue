<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/i/it2_9lb4h.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLNaNYcFh"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="it2_9lb4h"/></g></mask></defs><path mask="url(#SVGLNaNYcFh)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:arrow-circle-up" /></template>
