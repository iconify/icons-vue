<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/s/sgdy4u9pn.css';
import '../../css/e/euzfwrbhu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCATsPeGq"><g class="aql7dnt-u"><path class="sgdy4u9pn"/><path class="euzfwrbhu"/></g></mask></defs><path mask="url(#SVGCATsPeGq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:feelgood" /></template>
