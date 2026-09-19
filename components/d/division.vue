<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/ly3dcqbgo.css';
import '../../css/k/kd00u0b-i.css';
import '../../css/j/jxsnms7hz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSDfsTcUV"><g class="aql7dnt-u"><circle class="ly3dcqbgo"/><circle class="kd00u0b-i"/><path class="jxsnms7hz"/></g></mask></defs><path mask="url(#SVGSDfsTcUV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:division" /></template>
