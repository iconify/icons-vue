<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/u/us8q08b6o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAtk1EcxV"><g class="ufeehvblu"><path class="oo_vs07_g"/><path class="us8q08b6o"/></g></mask></defs><path mask="url(#SVGAtk1EcxV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:circle-right-down" /></template>
