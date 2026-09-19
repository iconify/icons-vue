<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv130ab-t.css';
import '../../css/h/hez4fkboo.css';
import '../../css/v/vt-d02btz.css';
import '../../css/y/y93muob-f.css';
import '../../css/o/o0hyrubuf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGYMEchepy"><g class="hv130ab-t"><path class="hez4fkboo"/><path class="vt-d02btz"/><path class="y93muob-f"/><path class="o0hyrubuf"/></g></mask></defs><path mask="url(#SVGYMEchepy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:gate" /></template>
