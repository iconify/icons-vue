<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/u/uq8nfifpp.css';
import '../../css/i/iuda6xbum.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqgKvhdiB"><g class="aql7dnt-u"><path clip-rule="evenodd" class="uq8nfifpp"/><path class="iuda6xbum"/></g></mask></defs><path mask="url(#SVGqgKvhdiB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:forbid" /></template>
