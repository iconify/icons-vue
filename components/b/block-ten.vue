<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/adexpl72i.css';
import '../../css/d/d70u10bbk.css';
import '../../css/d/dov8vg2gk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIngd6caS"><g class="adexpl72i"><path class="d70u10bbk"/><path class="dov8vg2gk"/></g></mask></defs><path mask="url(#SVGIngd6caS)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:block-ten" /></template>
