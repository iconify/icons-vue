<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xlq2m0blx.css';
import '../../css/p/pot_04b4h.css';
import '../../css/d/dqujb-3pm.css';
import '../../css/j/jtilm806p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlRr3teka"><g class="v3_i3wktz"><path class="xlq2m0blx"/><path class="pot_04b4h"/><path class="dqujb-3pm"/><path class="jtilm806p"/></g></mask></defs><path mask="url(#SVGlRr3teka)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:fire-extinguisher-one" /></template>
