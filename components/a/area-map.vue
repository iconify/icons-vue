<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/g/g6ovlz6dh.css';
import '../../css/g/gazpy_epd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGwOZAOeIa"><g class="aql7dnt-u"><path class="g6ovlz6dh"/><path class="gazpy_epd"/></g></mask></defs><path mask="url(#SVGwOZAOeIa)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:area-map" /></template>
