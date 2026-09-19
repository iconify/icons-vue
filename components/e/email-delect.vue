<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/q/qtgswnn4u.css';
import '../../css/z/z78yszbru.css';
import '../../css/y/yxhlumb2n.css';
import '../../css/p/p1h0mh26u.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbZygNbsA"><g class="aql7dnt-u"><path class="qtgswnn4u"/><path class="z78yszbru"/><path class="yxhlumb2n"/><path class="p1h0mh26u"/></g></mask></defs><path mask="url(#SVGbZygNbsA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:email-delect" /></template>
