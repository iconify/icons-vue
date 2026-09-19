<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/w/w-h22mbss.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSpU8Zcif"><g class="aql7dnt-u"><rect class="h9qj9o6mz"/><path class="w-h22mbss"/></g></mask></defs><path mask="url(#SVGSpU8Zcif)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:left-square" /></template>
