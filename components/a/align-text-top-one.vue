<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/q/q2jwkhaeu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEvtLmcIV"><g class="v3_i3wktz"><rect class="h9qj9o6mz"/><path class="q2jwkhaeu"/></g></mask></defs><path mask="url(#SVGEvtLmcIV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-text-top-one" /></template>
