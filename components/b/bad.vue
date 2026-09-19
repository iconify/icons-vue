<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm7opcb8n.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkrBqIdmR"><path class="hm7opcb8n"/></mask></defs><path mask="url(#SVGkrBqIdmR)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bad" /></template>
