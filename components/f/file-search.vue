<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/b/bvncembqc.css';
import '../../css/y/yp3vjsbtd.css';
import '../../css/f/fy_-6tw5f.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFphxOexL"><g class="hv130ab-t"><path class="bvncembqc"/><path class="yp3vjsbtd"/><circle transform="rotate(45 33.485 33.485)" class="fy_-6tw5f"/></g></mask></defs><path mask="url(#SVGFphxOexL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-search" /></template>
