<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mzszod_2j.css';
import '../../css/c/c45mhr9-t.css';
import '../../css/i/i4m-rlb1z.css';
import '../../css/f/f8pr247sv.css';
import '../../css/y/ycvy21jmk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG6JKoKepx"><g class="s9cl3zbei"><circle class="mzszod_2j"/><path class="c45mhr9-t"/><circle class="i4m-rlb1z"/><path class="f8pr247sv"/><path class="ycvy21jmk"/></g></mask></defs><path mask="url(#SVG6JKoKepx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:death-star" /></template>
