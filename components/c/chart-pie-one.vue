<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/lh6ow3bkp.css';
import '../../css/j/jkqxc6rbv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGC9T2wcAH"><g class="aql7dnt-u"><path class="lh6ow3bkp"/><path class="jkqxc6rbv"/></g></mask></defs><path mask="url(#SVGC9T2wcAH)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:chart-pie-one" /></template>
