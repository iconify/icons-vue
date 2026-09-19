<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1_swcb_o.css';
import '../../css/p/p47c9-mcc.css';
import '../../css/j/jqjqplo7i.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLqEOxaPY"><g class="v1_swcb_o"><path class="p47c9-mcc"/><path class="jqjqplo7i"/></g></mask></defs><path mask="url(#SVGLqEOxaPY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:avocado" /></template>
