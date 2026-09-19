<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/p/p2f2uss-m.css';
import '../../css/q/qk_g53bfd.css';
import '../../css/o/ofgf3ebhn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGi9bVbdFm"><g class="aql7dnt-u"><circle class="p2f2uss-m"/><circle transform="matrix(-1 0 0 1 33.5 24.5)" class="qk_g53bfd"/><path class="ofgf3ebhn"/></g></mask></defs><path mask="url(#SVGi9bVbdFm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:glasses-one" /></template>
