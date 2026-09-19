<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dq9x4xjot.css';
import '../../css/s/sm85w8b7f.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2wgVdbzN"><g class="v3_i3wktz"><path class="dq9x4xjot"/><path clip-rule="evenodd" class="sm85w8b7f"/></g></mask></defs><path mask="url(#SVG2wgVdbzN)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hand-down" /></template>
