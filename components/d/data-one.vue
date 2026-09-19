<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/s/sa9ebpbox.css';
import '../../css/y/y4vjg0k3v.css';
import '../../css/v/vf4h32bmh.css';
import '../../css/i/ib2bsphlp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkV84McAz"><g class="aql7dnt-u"><ellipse class="sa9ebpbox"/><path class="y4vjg0k3v"/><path class="vf4h32bmh"/><path class="ib2bsphlp"/></g></mask></defs><path mask="url(#SVGkV84McAz)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:data-one" /></template>
