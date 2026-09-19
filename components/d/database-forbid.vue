<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/l/lcee_744z.css';
import '../../css/q/quqne-byv.css';
import '../../css/h/hdf6pbbtd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7IORnFZG"><g class="aql7dnt-u"><path class="lcee_744z"/><path class="quqne-byv"/><path class="hdf6pbbtd"/></g></mask></defs><path mask="url(#SVG7IORnFZG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:database-forbid" /></template>
