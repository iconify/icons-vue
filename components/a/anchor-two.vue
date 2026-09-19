<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/b/bb8tv3klv.css';
import '../../css/w/wdmnkdbcq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1BAsubKX"><g class="aql7dnt-u"><path class="bb8tv3klv"/><path clip-rule="evenodd" class="wdmnkdbcq"/></g></mask></defs><path mask="url(#SVG1BAsubKX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:anchor-two" /></template>
