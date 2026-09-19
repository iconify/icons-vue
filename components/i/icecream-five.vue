<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/s/sjxycbjzr.css';
import '../../css/x/xdjtwgb7o.css';
import '../../css/j/jbtaph4oz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlkr5ieYj"><g class="s9cl3zbei"><path class="sjxycbjzr"/><path class="xdjtwgb7o"/><path class="jbtaph4oz"/></g></mask></defs><path mask="url(#SVGlkr5ieYj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:icecream-five" /></template>
