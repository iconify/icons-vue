<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/u/u-54wpbwh.css';
import '../../css/a/abjxd4g5a.css';
import '../../css/i/ifwg-w9dt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEEPK9coB"><g class="hv130ab-t"><path class="u-54wpbwh"/><path class="abjxd4g5a"/><path class="ifwg-w9dt"/></g></mask></defs><path mask="url(#SVGEEPK9coB)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bottle-two" /></template>
