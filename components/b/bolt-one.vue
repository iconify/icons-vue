<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/z/zow-3zwzb.css';
import '../../css/p/pg_5h5m7z.css';
import '../../css/y/ywu8tfbvo.css';
import '../../css/e/e9m95gfak.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4isBwcig"><g class="s9cl3zbei"><path class="zow-3zwzb"/><path class="pg_5h5m7z"/><path class="ywu8tfbvo"/><path class="e9m95gfak"/></g></mask></defs><path mask="url(#SVG4isBwcig)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:bolt-one" /></template>
