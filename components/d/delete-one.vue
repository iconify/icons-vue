<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hit3bi0-v.css';
import '../../css/g/g1-qxqbur.css';
import '../../css/j/jgg56cbfn.css';
import '../../css/v/vxzaw_bgf.css';
import '../../css/d/dml3zeblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="g1-qxqbur"/><path class="jgg56cbfn"/><path clip-rule="evenodd" class="vxzaw_bgf"/><path class="dml3zeblg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:delete-one" /></template>
