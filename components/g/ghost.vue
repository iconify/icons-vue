<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/c/cf1w4fbaw.css';
import '../../css/r/rpgbrbc4i.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGln6CWcqi"><g class="v3_i3wktz"><path class="cf1w4fbaw"/><path class="rpgbrbc4i"/></g></mask></defs><path mask="url(#SVGln6CWcqi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:ghost" /></template>
