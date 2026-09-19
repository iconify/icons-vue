<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/k/ko35661_d.css';
import '../../css/p/pznbfkwvh.css';
import '../../css/d/dn4j-pb5x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOvFlObFj"><g class="aql7dnt-u"><path class="ko35661_d"/><path class="pznbfkwvh"/><path class="dn4j-pb5x"/></g></mask></defs><path mask="url(#SVGOvFlObFj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:four-point-connection" /></template>
