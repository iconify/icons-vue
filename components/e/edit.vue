<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x3u46_gnm.css';
import '../../css/a/aqj7hfbjq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoYDnedpV"><g class="v3_i3wktz"><path class="x3u46_gnm"/><path class="aqj7hfbjq"/></g></mask></defs><path mask="url(#SVGoYDnedpV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:edit" /></template>
