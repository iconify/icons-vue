<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/ay21un4ba.css';
import '../../css/i/iv0tfobzy.css';
import '../../css/b/b9aamtbca.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHRAHueGK"><g class="v3_i3wktz"><path class="ay21un4ba"/><path class="iv0tfobzy"/><path class="b9aamtbca"/></g></mask></defs><path mask="url(#SVGHRAHueGK)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:game-handle" /></template>
