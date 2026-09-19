<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/r-jxe9bpv.css';
import '../../css/o/omnpcg9gc.css';
import '../../css/z/zjbgnh96p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgFAqpCEZ"><g class="v3_i3wktz"><path class="r-jxe9bpv"/><path class="omnpcg9gc"/><path class="zjbgnh96p"/></g></mask></defs><path mask="url(#SVGgFAqpCEZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:invert-camera" /></template>
