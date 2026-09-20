<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/fc8-g1bvj.css';
import '../../css/h/hy12j1abm.css';
import '../../css/r/r1fxoub4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="fc8-g1bvj"/><path class="hy12j1abm"/><path class="r1fxoub4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:code" /></template>
