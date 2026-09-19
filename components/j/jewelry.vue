<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mzszod_2j.css';
import '../../css/p/p5_dofibb.css';
import '../../css/p/p7hn-sb3e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBoBbid3e"><g class="s9cl3zbei"><circle class="mzszod_2j"/><path class="p5_dofibb"/><path class="p7hn-sb3e"/></g></mask></defs><path mask="url(#SVGBoBbid3e)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:jewelry" /></template>
