<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xdm0-sb7l.css';
import '../../css/y/yd5ssobgf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwWf9HgGd"><g class="v3_i3wktz"><path class="xdm0-sb7l"/><path clip-rule="evenodd" class="yd5ssobgf"/></g></mask></defs><path mask="url(#SVGwWf9HgGd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hand-left" /></template>
