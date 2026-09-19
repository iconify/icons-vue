<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/j/jlnr15bxu.css';
import '../../css/i/i5-ng-btb.css';
import '../../css/t/tbfk-_6ot.css';
import '../../css/l/l-90x2_qh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGps2vrDJY"><g class="s9cl3zbei"><path class="jlnr15bxu"/><path class="i5-ng-btb"/><path class="tbfk-_6ot"/><path class="l-90x2_qh"/></g></mask></defs><path mask="url(#SVGps2vrDJY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:cola" /></template>
