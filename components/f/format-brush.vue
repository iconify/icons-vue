<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qdzwi4b4l.css';
import '../../css/v/vaa0ik_1j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPm4kxc4w"><g class="v3_i3wktz"><path class="qdzwi4b4l"/><path class="vaa0ik_1j"/></g></mask></defs><path mask="url(#SVGPm4kxc4w)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:format-brush" /></template>
