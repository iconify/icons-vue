<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/s/scql5blaj.css';
import '../../css/f/fw8rx6b9c.css';
import '../../css/c/cuh8gyztp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5LxiZdOk"><g class="aql7dnt-u"><path class="scql5blaj"/><path class="fw8rx6b9c"/><path class="cuh8gyztp"/></g></mask></defs><path mask="url(#SVG5LxiZdOk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:enter-key" /></template>
