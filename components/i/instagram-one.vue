<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_swcb_o.css';
import '../../css/a/aoabsmt9b.css';
import '../../css/c/cjjtizl0b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEIHzIcGC"><g class="v1_swcb_o"><circle class="aoabsmt9b"/><path class="cjjtizl0b"/></g></mask></defs><path mask="url(#SVGEIHzIcGC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:instagram-one" /></template>
