<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/smw8n4bjx.css';
import '../../css/m/mbvagtp9n.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGELUQo9DW"><g class="v3_i3wktz"><path class="smw8n4bjx"/><path class="mbvagtp9n"/></g></mask></defs><path mask="url(#SVGELUQo9DW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:card-two" /></template>
