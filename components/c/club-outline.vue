<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vpxhribda.css';
import '../../css/w/w3bp2bcky.css';
import '../../css/u/un6ecob_e.css';
import '../../css/q/qccfeuj6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vpxhribda"/><path class="w3bp2bcky"/><path class="un6ecob_e"/><path class="qccfeuj6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:club-outline" /></template>
