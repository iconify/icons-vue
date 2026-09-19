<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mzszod_2j.css';
import '../../css/r/rt4zo2bpe.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaVrrHcAf"><g class="s9cl3zbei"><circle class="mzszod_2j"/><path class="rt4zo2bpe"/></g></mask></defs><path mask="url(#SVGaVrrHcAf)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:flashlamp" /></template>
