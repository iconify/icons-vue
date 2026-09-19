<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/fbo_5_dgq.css';
import '../../css/b/bcycd7i_s.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG441SvbSD"><g class="aql7dnt-u"><path class="fbo_5_dgq"/><path class="bcycd7i_s"/></g></mask></defs><path mask="url(#SVG441SvbSD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:badge" /></template>
