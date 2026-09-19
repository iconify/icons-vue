<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0_m-9bfs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzYmnGefN"><path class="n0_m-9bfs"/></mask></defs><path mask="url(#SVGzYmnGefN)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bat" /></template>
