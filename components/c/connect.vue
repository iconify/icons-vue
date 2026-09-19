<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/n/nr6ltb85s.css';
import '../../css/q/q6-g7vdkb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHwHCXTDV"><g class="aql7dnt-u"><path clip-rule="evenodd" class="nr6ltb85s"/><path class="q6-g7vdkb"/></g></mask></defs><path mask="url(#SVGHwHCXTDV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:connect" /></template>
