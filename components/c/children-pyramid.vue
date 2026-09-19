<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/h12rk9boh.css';
import '../../css/u/u90vnfbeh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2FuPZbGp"><g class="aql7dnt-u"><path class="h12rk9boh"/><path class="u90vnfbeh"/></g></mask></defs><path mask="url(#SVG2FuPZbGp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:children-pyramid" /></template>
