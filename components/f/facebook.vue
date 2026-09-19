<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/va4l-rdig.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfIrXF2an"><path class="va4l-rdig"/></mask></defs><path mask="url(#SVGfIrXF2an)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:facebook" /></template>
