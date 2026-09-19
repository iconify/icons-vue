<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bl312vbyc.css';
import '../../css/e/e6-_wnblc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHVLLCeHM"><g class="v3_i3wktz"><path class="bl312vbyc"/><path class="e6-_wnblc"/></g></mask></defs><path mask="url(#SVGHVLLCeHM)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:laptop-one" /></template>
