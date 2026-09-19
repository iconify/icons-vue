<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/y/y3yom5bcd.css';
import '../../css/k/knxvrwb6y.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEoMuNbDJ"><g class="aql7dnt-u"><path class="y3yom5bcd"/><path class="knxvrwb6y"/></g></mask></defs><path mask="url(#SVGEoMuNbDJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:leaves-two" /></template>
