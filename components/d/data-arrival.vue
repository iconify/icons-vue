<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/o3eo20bpg.css';
import '../../css/j/jgkv41b5o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJ1qr9dfU"><g class="v3_i3wktz"><path clip-rule="evenodd" class="o3eo20bpg"/><path class="jgkv41b5o"/></g></mask></defs><path mask="url(#SVGJ1qr9dfU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:data-arrival" /></template>
