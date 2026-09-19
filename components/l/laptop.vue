<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qrymgbcbz.css';
import '../../css/o/otz57pxwg.css';
import '../../css/k/krtelgb7b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMlZleJHc"><g class="aql7dnt-u"><path class="qrymgbcbz"/><path class="otz57pxwg"/><path class="krtelgb7b"/></g></mask></defs><path mask="url(#SVGMlZleJHc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:laptop" /></template>
