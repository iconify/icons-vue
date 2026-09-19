<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/oo_vs07_g.css';
import '../../css/w/wmm6gzb0b.css';
import '../../css/k/kpxxoib8h.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGKvA2Vbtk"><g class="s9cl3zbei"><path class="oo_vs07_g"/><path class="wmm6gzb0b"/><path class="kpxxoib8h"/></g></mask></defs><path mask="url(#SVGKvA2Vbtk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:benz" /></template>
