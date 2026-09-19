<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rohhhzb0l.css';
import '../../css/g/g1-qxqbur.css';
import '../../css/j/jgg56cbfn.css';
import '../../css/m/moyr37lyl.css';
import '../../css/d/dml3zeblg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGj2otHeBW"><g class="rohhhzb0l"><path class="g1-qxqbur"/><path class="jgg56cbfn"/><path clip-rule="evenodd" class="moyr37lyl"/><path class="dml3zeblg"/></g></mask></defs><path mask="url(#SVGj2otHeBW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:delete-one" /></template>
