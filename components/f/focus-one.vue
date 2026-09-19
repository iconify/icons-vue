<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kucvonbff.css';
import '../../css/b/bwxwxu62q.css';
import '../../css/l/l-o0nybcd.css';
import '../../css/f/fqvsswb6x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGV7PGtcWW"><g class="ft5dv1b6b"><path class="kucvonbff"/><path class="bwxwxu62q"/><path class="l-o0nybcd"/><path class="fqvsswb6x"/></g></mask></defs><path mask="url(#SVGV7PGtcWW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:focus-one" /></template>
