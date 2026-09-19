<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/lfaqxlbsl.css';
import '../../css/m/mxqp5wvsi.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgnWzveXa"><g class="aql7dnt-u"><path class="lfaqxlbsl"/><path class="mxqp5wvsi"/></g></mask></defs><path mask="url(#SVGgnWzveXa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:escalators" /></template>
