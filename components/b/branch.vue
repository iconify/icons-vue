<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/g7m1m763r.css';
import '../../css/b/bqvh2xbzc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3kdFIerk"><g class="v3_i3wktz"><path class="g7m1m763r"/><path class="bqvh2xbzc"/></g></mask></defs><path mask="url(#SVG3kdFIerk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:branch" /></template>
