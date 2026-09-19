<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/h/hgyr1h5yj.css';
import '../../css/i/ifj0fdciu.css';
import '../../css/w/wve1_ubeu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKIKbKdgr"><g class="aql7dnt-u"><path class="hgyr1h5yj"/><path class="ifj0fdciu"/><path class="wve1_ubeu"/></g></mask></defs><path mask="url(#SVGKIKbKdgr)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:chair" /></template>
