<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/a/a_ete1bey.css';
import '../../css/e/eo9hd3bdj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGu4ecWcln"><g class="aql7dnt-u"><circle class="a_ete1bey"/><path clip-rule="evenodd" class="eo9hd3bdj"/></g></mask></defs><path mask="url(#SVGu4ecWcln)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:handle-b" /></template>
