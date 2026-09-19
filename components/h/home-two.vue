<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xrsuk-b2x.css';
import '../../css/g/gcng8vetl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQZPoheQf"><g class="v3_i3wktz"><path class="xrsuk-b2x"/><path class="gcng8vetl"/></g></mask></defs><path mask="url(#SVGQZPoheQf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:home-two" /></template>
