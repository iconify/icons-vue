<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/y/ymsi6fbor.css';
import '../../css/i/idyp2ss1r.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<mask id="svgIDa"><g class="aql7dnt-u"><path clip-rule="evenodd" class="ymsi6fbor"/><path class="idyp2ss1r"/></g></mask><path mask="url(#svgIDa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:behance" /></template>
